# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `es2015 > yield > function-name-function-declaration-inside-generator`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	directives: Array []
	filename: "es2015/yield/function-name-function-declaration-inside-generator/input.js"
	hasHoistedVars: false
	interpreter: undefined
	mtime: undefined
	sourceType: "script"
	syntax: Array []
	loc: Object {
		filename: "es2015/yield/function-name-function-declaration-inside-generator/input.js"
		end: Object {
			column: 1
			line: 3
		}
		start: Object {
			column: 0
			line: 1
		}
	}
	diagnostics: Array [
		Object {
			origins: Array [Object {category: "parse/js"}]
			description: Object {
				advice: Array []
				category: "parse/js"
				message: MARKUP {parts: Array [RAW_MARKUP {value: "Can not use 'yield' as identifier inside a generator"}]}
			}
			location: Object {
				filename: "es2015/yield/function-name-function-declaration-inside-generator/input.js"
				mtime: undefined
				sourceText: undefined
				end: Object {
					column: 16
					line: 2
				}
				start: Object {
					column: 11
					line: 2
				}
			}
		}
	]
	body: Array [
		JSFunctionDeclaration {
			id: JSBindingIdentifier {
				name: "fn"
				loc: Object {
					filename: "es2015/yield/function-name-function-declaration-inside-generator/input.js"
					identifierName: "fn"
					end: Object {
						column: 12
						line: 1
					}
					start: Object {
						column: 10
						line: 1
					}
				}
			}
			loc: Object {
				filename: "es2015/yield/function-name-function-declaration-inside-generator/input.js"
				end: Object {
					column: 1
					line: 3
				}
				start: Object {
					column: 0
					line: 1
				}
			}
			head: JSFunctionHead {
				async: false
				generator: true
				hasHoistedVars: false
				params: Array []
				rest: undefined
				returnType: undefined
				thisType: undefined
				typeParameters: undefined
				loc: Object {
					filename: "es2015/yield/function-name-function-declaration-inside-generator/input.js"
					end: Object {
						column: 14
						line: 1
					}
					start: Object {
						column: 12
						line: 1
					}
				}
			}
			body: JSBlockStatement {
				directives: Array []
				loc: Object {
					filename: "es2015/yield/function-name-function-declaration-inside-generator/input.js"
					end: Object {
						column: 1
						line: 3
					}
					start: Object {
						column: 15
						line: 1
					}
				}
				body: Array [
					JSFunctionDeclaration {
						id: JSBindingIdentifier {
							name: "yield"
							loc: Object {
								filename: "es2015/yield/function-name-function-declaration-inside-generator/input.js"
								identifierName: "yield"
								end: Object {
									column: 16
									line: 2
								}
								start: Object {
									column: 11
									line: 2
								}
							}
						}
						loc: Object {
							filename: "es2015/yield/function-name-function-declaration-inside-generator/input.js"
							end: Object {
								column: 21
								line: 2
							}
							start: Object {
								column: 2
								line: 2
							}
						}
						body: JSBlockStatement {
							body: Array []
							directives: Array []
							loc: Object {
								filename: "es2015/yield/function-name-function-declaration-inside-generator/input.js"
								end: Object {
									column: 21
									line: 2
								}
								start: Object {
									column: 19
									line: 2
								}
							}
						}
						head: JSFunctionHead {
							async: false
							generator: false
							hasHoistedVars: false
							params: Array []
							rest: undefined
							returnType: undefined
							thisType: undefined
							typeParameters: undefined
							loc: Object {
								filename: "es2015/yield/function-name-function-declaration-inside-generator/input.js"
								end: Object {
									column: 18
									line: 2
								}
								start: Object {
									column: 16
									line: 2
								}
							}
						}
					}
				]
			}
		}
	]
}
```

### `diagnostics`

```

 es2015/yield/function-name-function-declaration-inside-generator/input.js:2:11 parse/js ━━━━━━━━━━━

  ✖ Can not use 'yield' as identifier inside a generator

    1 │ function* fn() {
  > 2 │   function yield() {}
      │            ^^^^^
    3 │ }

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

✖ Found 1 problem

```
