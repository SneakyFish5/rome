# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romefrontend/js-parser/index.test.ts --update-snapshots` to update.

## `esprima > expression-primary-object > migrated_0038`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	diagnostics: Array []
	directives: Array []
	filename: "input.js"
	hasHoistedVars: false
	interpreter: undefined
	mtime: undefined
	sourceType: "script"
	syntax: Array []
	loc: Object {
		filename: "input.js"
		end: Object {
			column: 16
			index: 16
			line: 1
		}
		start: Object {
			column: 0
			index: 0
			line: 1
		}
	}
	body: Array [
		JSExpressionStatement {
			loc: Object {
				filename: "input.js"
				end: Object {
					column: 16
					index: 16
					line: 1
				}
				start: Object {
					column: 0
					index: 0
					line: 1
				}
			}
			expression: JSObjectExpression {
				loc: Object {
					filename: "input.js"
					end: Object {
						column: 15
						index: 15
						line: 1
					}
					start: Object {
						column: 1
						index: 1
						line: 1
					}
				}
				properties: Array [
					JSObjectMethod {
						kind: "set"
						key: JSStaticPropertyKey {
							value: JSIdentifier {
								name: "x"
								loc: Object {
									filename: "input.js"
									identifierName: "x"
									end: Object {
										column: 7
										index: 7
										line: 1
									}
									start: Object {
										column: 6
										index: 6
										line: 1
									}
								}
							}
							loc: Object {
								filename: "input.js"
								end: Object {
									column: 7
									index: 7
									line: 1
								}
								start: Object {
									column: 6
									index: 6
									line: 1
								}
							}
						}
						loc: Object {
							filename: "input.js"
							end: Object {
								column: 14
								index: 14
								line: 1
							}
							start: Object {
								column: 2
								index: 2
								line: 1
							}
						}
						body: JSBlockStatement {
							body: Array []
							directives: Array []
							loc: Object {
								filename: "input.js"
								end: Object {
									column: 14
									index: 14
									line: 1
								}
								start: Object {
									column: 12
									index: 12
									line: 1
								}
							}
						}
						head: JSFunctionHead {
							async: false
							generator: false
							hasHoistedVars: false
							rest: undefined
							returnType: undefined
							thisType: undefined
							typeParameters: undefined
							loc: Object {
								filename: "input.js"
								end: Object {
									column: 12
									index: 12
									line: 1
								}
								start: Object {
									column: 7
									index: 7
									line: 1
								}
							}
							params: Array [
								JSBindingAssignmentPattern {
									loc: Object {
										filename: "input.js"
										end: Object {
											column: 11
											index: 11
											line: 1
										}
										start: Object {
											column: 8
											index: 8
											line: 1
										}
									}
									right: JSNumericLiteral {
										value: 0
										format: undefined
										loc: Object {
											filename: "input.js"
											end: Object {
												column: 11
												index: 11
												line: 1
											}
											start: Object {
												column: 10
												index: 10
												line: 1
											}
										}
									}
									left: JSBindingIdentifier {
										name: "a"
										loc: Object {
											filename: "input.js"
											identifierName: "a"
											end: Object {
												column: 9
												index: 9
												line: 1
											}
											start: Object {
												column: 8
												index: 8
												line: 1
											}
										}
										meta: JSPatternMeta {
											optional: undefined
											typeAnnotation: undefined
											loc: Object {
												filename: "input.js"
												end: Object {
													column: 9
													index: 9
													line: 1
												}
												start: Object {
													column: 8
													index: 8
													line: 1
												}
											}
										}
									}
								}
							]
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
✔ No known problems!

```