# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/js-parser/index.test.ts --update-snapshots` to update.

## `esprima > es2015-arrow-function > object-binding-pattern-invalid-nested-param`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	directives: Array []
	filename: "esprima/es2015-arrow-function/object-binding-pattern-invalid-nested-param/input.js"
	hasHoistedVars: false
	interpreter: undefined
	mtime: undefined
	sourceType: "script"
	syntax: Array []
	loc: Object {
		filename: "esprima/es2015-arrow-function/object-binding-pattern-invalid-nested-param/input.js"
		end: Object {
			column: 0
			index: 55
			line: 2
		}
		start: Object {
			column: 0
			index: 0
			line: 1
		}
	}
	diagnostics: Array [
		Object {
			origins: Array [Object {category: "parse/js"}]
			description: Object {
				advice: Array []
				category: "parse/js"
				message: MARKUP {parts: Array [RAW_MARKUP {value: "Binding member expression"}]}
			}
			location: Object {
				filename: "esprima/es2015-arrow-function/object-binding-pattern-invalid-nested-param/input.js"
				mtime: undefined
				sourceText: undefined
				end: Object {
					column: 28
					index: 28
					line: 1
				}
				start: Object {
					column: 24
					index: 24
					line: 1
				}
			}
		}
	]
	body: Array [
		JSExpressionStatement {
			loc: Object {
				filename: "esprima/es2015-arrow-function/object-binding-pattern-invalid-nested-param/input.js"
				end: Object {
					column: 54
					index: 54
					line: 1
				}
				start: Object {
					column: 0
					index: 0
					line: 1
				}
			}
			expression: JSArrowFunctionExpression {
				loc: Object {
					filename: "esprima/es2015-arrow-function/object-binding-pattern-invalid-nested-param/input.js"
					end: Object {
						column: 53
						index: 53
						line: 1
					}
					start: Object {
						column: 0
						index: 0
						line: 1
					}
				}
				body: JSNumericLiteral {
					value: 0
					format: undefined
					loc: Object {
						filename: "esprima/es2015-arrow-function/object-binding-pattern-invalid-nested-param/input.js"
						end: Object {
							column: 53
							index: 53
							line: 1
						}
						start: Object {
							column: 52
							index: 52
							line: 1
						}
					}
				}
				head: JSFunctionHead {
					async: false
					hasHoistedVars: false
					rest: undefined
					returnType: undefined
					thisType: undefined
					loc: Object {
						filename: "esprima/es2015-arrow-function/object-binding-pattern-invalid-nested-param/input.js"
						end: Object {
							column: 52
							index: 52
							line: 1
						}
						start: Object {
							column: 0
							index: 0
							line: 1
						}
					}
					params: Array [
						JSBindingArrayPattern {
							rest: undefined
							loc: Object {
								filename: "esprima/es2015-arrow-function/object-binding-pattern-invalid-nested-param/input.js"
								end: Object {
									column: 49
									index: 49
									line: 1
								}
								start: Object {
									column: 1
									index: 1
									line: 1
								}
							}
							elements: Array [
								JSBindingArrayPattern {
									rest: undefined
									loc: Object {
										filename: "esprima/es2015-arrow-function/object-binding-pattern-invalid-nested-param/input.js"
										end: Object {
											column: 48
											index: 48
											line: 1
										}
										start: Object {
											column: 2
											index: 2
											line: 1
										}
									}
									elements: Array [
										JSBindingArrayPattern {
											rest: undefined
											loc: Object {
												filename: "esprima/es2015-arrow-function/object-binding-pattern-invalid-nested-param/input.js"
												end: Object {
													column: 47
													index: 47
													line: 1
												}
												start: Object {
													column: 3
													index: 3
													line: 1
												}
											}
											elements: Array [
												JSBindingArrayPattern {
													rest: undefined
													loc: Object {
														filename: "esprima/es2015-arrow-function/object-binding-pattern-invalid-nested-param/input.js"
														end: Object {
															column: 46
															index: 46
															line: 1
														}
														start: Object {
															column: 4
															index: 4
															line: 1
														}
													}
													elements: Array [
														JSBindingArrayPattern {
															rest: undefined
															loc: Object {
																filename: "esprima/es2015-arrow-function/object-binding-pattern-invalid-nested-param/input.js"
																end: Object {
																	column: 45
																	index: 45
																	line: 1
																}
																start: Object {
																	column: 5
																	index: 5
																	line: 1
																}
															}
															elements: Array [
																JSBindingArrayPattern {
																	rest: undefined
																	loc: Object {
																		filename: "esprima/es2015-arrow-function/object-binding-pattern-invalid-nested-param/input.js"
																		end: Object {
																			column: 44
																			index: 44
																			line: 1
																		}
																		start: Object {
																			column: 6
																			index: 6
																			line: 1
																		}
																	}
																	elements: Array [
																		JSBindingArrayPattern {
																			rest: undefined
																			loc: Object {
																				filename: "esprima/es2015-arrow-function/object-binding-pattern-invalid-nested-param/input.js"
																				end: Object {
																					column: 43
																					index: 43
																					line: 1
																				}
																				start: Object {
																					column: 7
																					index: 7
																					line: 1
																				}
																			}
																			elements: Array [
																				JSBindingArrayPattern {
																					rest: undefined
																					loc: Object {
																						filename: "esprima/es2015-arrow-function/object-binding-pattern-invalid-nested-param/input.js"
																						end: Object {
																							column: 42
																							index: 42
																							line: 1
																						}
																						start: Object {
																							column: 8
																							index: 8
																							line: 1
																						}
																					}
																					elements: Array [
																						JSBindingArrayPattern {
																							rest: undefined
																							loc: Object {
																								filename: "esprima/es2015-arrow-function/object-binding-pattern-invalid-nested-param/input.js"
																								end: Object {
																									column: 41
																									index: 41
																									line: 1
																								}
																								start: Object {
																									column: 9
																									index: 9
																									line: 1
																								}
																							}
																							elements: Array [
																								JSBindingArrayPattern {
																									rest: undefined
																									loc: Object {
																										filename: "esprima/es2015-arrow-function/object-binding-pattern-invalid-nested-param/input.js"
																										end: Object {
																											column: 40
																											index: 40
																											line: 1
																										}
																										start: Object {
																											column: 10
																											index: 10
																											line: 1
																										}
																									}
																									elements: Array [
																										JSBindingArrayPattern {
																											rest: undefined
																											loc: Object {
																												filename: "esprima/es2015-arrow-function/object-binding-pattern-invalid-nested-param/input.js"
																												end: Object {
																													column: 39
																													index: 39
																													line: 1
																												}
																												start: Object {
																													column: 11
																													index: 11
																													line: 1
																												}
																											}
																											elements: Array [
																												JSBindingArrayPattern {
																													rest: undefined
																													loc: Object {
																														filename: "esprima/es2015-arrow-function/object-binding-pattern-invalid-nested-param/input.js"
																														end: Object {
																															column: 38
																															index: 38
																															line: 1
																														}
																														start: Object {
																															column: 12
																															index: 12
																															line: 1
																														}
																													}
																													elements: Array [
																														JSBindingArrayPattern {
																															rest: undefined
																															loc: Object {
																																filename: "esprima/es2015-arrow-function/object-binding-pattern-invalid-nested-param/input.js"
																																end: Object {
																																	column: 37
																																	index: 37
																																	line: 1
																																}
																																start: Object {
																																	column: 13
																																	index: 13
																																	line: 1
																																}
																															}
																															elements: Array [
																																JSBindingArrayPattern {
																																	rest: undefined
																																	loc: Object {
																																		filename: "esprima/es2015-arrow-function/object-binding-pattern-invalid-nested-param/input.js"
																																		end: Object {
																																			column: 36
																																			index: 36
																																			line: 1
																																		}
																																		start: Object {
																																			column: 14
																																			index: 14
																																			line: 1
																																		}
																																	}
																																	elements: Array [
																																		JSBindingArrayPattern {
																																			rest: undefined
																																			loc: Object {
																																				filename: "esprima/es2015-arrow-function/object-binding-pattern-invalid-nested-param/input.js"
																																				end: Object {
																																					column: 35
																																					index: 35
																																					line: 1
																																				}
																																				start: Object {
																																					column: 15
																																					index: 15
																																					line: 1
																																				}
																																			}
																																			elements: Array [
																																				JSBindingArrayPattern {
																																					rest: undefined
																																					loc: Object {
																																						filename: "esprima/es2015-arrow-function/object-binding-pattern-invalid-nested-param/input.js"
																																						end: Object {
																																							column: 34
																																							index: 34
																																							line: 1
																																						}
																																						start: Object {
																																							column: 16
																																							index: 16
																																							line: 1
																																						}
																																					}
																																					elements: Array [
																																						JSBindingArrayPattern {
																																							rest: undefined
																																							loc: Object {
																																								filename: "esprima/es2015-arrow-function/object-binding-pattern-invalid-nested-param/input.js"
																																								end: Object {
																																									column: 33
																																									index: 33
																																									line: 1
																																								}
																																								start: Object {
																																									column: 17
																																									index: 17
																																									line: 1
																																								}
																																							}
																																							elements: Array [
																																								JSBindingArrayPattern {
																																									rest: undefined
																																									loc: Object {
																																										filename: "esprima/es2015-arrow-function/object-binding-pattern-invalid-nested-param/input.js"
																																										end: Object {
																																											column: 32
																																											index: 32
																																											line: 1
																																										}
																																										start: Object {
																																											column: 18
																																											index: 18
																																											line: 1
																																										}
																																									}
																																									elements: Array [
																																										JSBindingArrayPattern {
																																											rest: undefined
																																											loc: Object {
																																												filename: "esprima/es2015-arrow-function/object-binding-pattern-invalid-nested-param/input.js"
																																												end: Object {
																																													column: 31
																																													index: 31
																																													line: 1
																																												}
																																												start: Object {
																																													column: 19
																																													index: 19
																																													line: 1
																																												}
																																											}
																																											elements: Array [
																																												JSBindingArrayPattern {
																																													rest: undefined
																																													loc: Object {
																																														filename: "esprima/es2015-arrow-function/object-binding-pattern-invalid-nested-param/input.js"
																																														end: Object {
																																															column: 30
																																															index: 30
																																															line: 1
																																														}
																																														start: Object {
																																															column: 20
																																															index: 20
																																															line: 1
																																														}
																																													}
																																													elements: Array [
																																														JSBindingObjectPattern {
																																															rest: undefined
																																															loc: Object {
																																																filename: "esprima/es2015-arrow-function/object-binding-pattern-invalid-nested-param/input.js"
																																																end: Object {
																																																	column: 29
																																																	index: 29
																																																	line: 1
																																																}
																																																start: Object {
																																																	column: 21
																																																	index: 21
																																																	line: 1
																																																}
																																															}
																																															properties: Array [
																																																JSBindingObjectPatternProperty {
																																																	key: JSStaticPropertyKey {
																																																		value: JSIdentifier {
																																																			name: "a"
																																																			loc: Object {
																																																				filename: "esprima/es2015-arrow-function/object-binding-pattern-invalid-nested-param/input.js"
																																																				identifierName: "a"
																																																				end: Object {
																																																					column: 23
																																																					index: 23
																																																					line: 1
																																																				}
																																																				start: Object {
																																																					column: 22
																																																					index: 22
																																																					line: 1
																																																				}
																																																			}
																																																		}
																																																		loc: Object {
																																																			filename: "esprima/es2015-arrow-function/object-binding-pattern-invalid-nested-param/input.js"
																																																			end: Object {
																																																				column: 23
																																																				index: 23
																																																				line: 1
																																																			}
																																																			start: Object {
																																																				column: 22
																																																				index: 22
																																																				line: 1
																																																			}
																																																		}
																																																	}
																																																	value: JSBindingIdentifier {
																																																		name: "X"
																																																		loc: Object {
																																																			filename: "esprima/es2015-arrow-function/object-binding-pattern-invalid-nested-param/input.js"
																																																			end: Object {
																																																				column: 28
																																																				index: 28
																																																				line: 1
																																																			}
																																																			start: Object {
																																																				column: 24
																																																				index: 24
																																																				line: 1
																																																			}
																																																		}
																																																	}
																																																	loc: Object {
																																																		filename: "esprima/es2015-arrow-function/object-binding-pattern-invalid-nested-param/input.js"
																																																		end: Object {
																																																			column: 28
																																																			index: 28
																																																			line: 1
																																																		}
																																																		start: Object {
																																																			column: 22
																																																			index: 22
																																																			line: 1
																																																		}
																																																	}
																																																}
																																															]
																																														}
																																													]
																																												}
																																											]
																																										}
																																									]
																																								}
																																							]
																																						}
																																					]
																																				}
																																			]
																																		}
																																	]
																																}
																															]
																														}
																													]
																												}
																											]
																										}
																									]
																								}
																							]
																						}
																					]
																				}
																			]
																		}
																	]
																}
															]
														}
													]
												}
											]
										}
									]
								}
							]
						}
					]
				}
			}
		}
	]
}
```

### `diagnostics`

```

 esprima/es2015-arrow-function/object-binding-pattern-invalid-nested-param/input.js:1:24 parse/js ━━

  ✖ Binding member expression

    ([[[[[[[[[[[[[[[[[[[[{a:b[0]}]]]]]]]]]]]]]]]]]]]])=>0;
                            ^^^^

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

✖ Found 1 problem

```