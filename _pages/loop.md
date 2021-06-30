---
layout: defaultBlank
title: Loop Demo
permalink: /loop
---

<h2>Loop Example</h2>

```javascript
var objects = [
        {
            type: 'RDC', 
            data: { 
                RiskScore: 34 
                }
        },
                {
            type: 'RDC', 
            data: { 
                RiskScore: 32 
                }
        }
    ];
var rules = [
        {
            dataType: 'number', 
            expectedValue: 34
        },
        {
            dataType: 'number', 
            expectedValue: 344
        },
    ];
```



<script>
var obj = {
  "data": {
    "id": "string",
    "status": "COMPLETE",
    "reviewStatus": "ALERT",
    "portfolioMonitoring": false,
    "loadOnly": false,
    "globalSearch": false,
    "reporting": "string",
    "tracking": "string",
    "gridPersonPartyInfo": {
      "partyContext": {
        "note": "string"
      },
      "pictures": {
        "picture": [
          {
            "pictureTyp": "string",
            "pictureData": {
              "dataSource": {
                "name": "string",
                "inputStream": {},
                "contentType": "string",
                "outputStream": {}
              },
              "name": "string",
              "inputStream": {},
              "content": {},
              "contentType": "string",
              "outputStream": {},
              "transferDataFlavors": [
                {
                  "mimeType": "string",
                  "humanPresentableName": "string",
                  "defaultRepresentationClassAsString": "string",
                  "flavorJavaFileListType": false,
                  "flavorRemoteObjectType": false,
                  "flavorSerializedObjectType": false,
                  "flavorTextType": false,
                  "mimeTypeSerializedObject": false,
                  "representationClassByteBuffer": false,
                  "representationClassCharBuffer": false,
                  "representationClassInputStream": false,
                  "representationClassReader": false,
                  "representationClassRemote": false,
                  "representationClassSerializable": false,
                  "primaryType": "string",
                  "subType": "string"
                }
              ],
              "preferredCommands": [
                {
                  "commandName": "string",
                  "commandClass": "string"
                }
              ],
              "allCommands": [
                {
                  "commandName": "string",
                  "commandClass": "string"
                }
              ]
            }
          }
        ]
      },
      "attribute": [
        {
          "attCode": "string",
          "attDesc": "string",
          "attVal": "string"
        }
      ],
      "gridPersonData": {
        "gridContact": {
          "addr": {
            "addr1": "string",
            "city": "string",
            "stateProv": "string",
            "postalCode": "string",
            "countryCode": {
              "countryCodeValue": "string"
            }
          }
        },
        "entityIdentifier": "string",
        "personName": {
          "fullName": "string",
          "familyName": "string",
          "givenName": "string",
          "middleName": "string"
        }
      },
      "birthDt": "2021-06-30T12:35:40.929Z",
      "age": 0,
      "sex": "M"
    },
    "gridOrgPartyInfo": {
      "partyContext": {
        "note": "string"
      },
      "pictures": {
        "picture": [
          {
            "pictureTyp": "string",
            "pictureData": {
              "dataSource": {
                "name": "string",
                "inputStream": {},
                "contentType": "string",
                "outputStream": {}
              },
              "name": "string",
              "inputStream": {},
              "content": {},
              "contentType": "string",
              "outputStream": {},
              "transferDataFlavors": [
                {
                  "mimeType": "string",
                  "humanPresentableName": "string",
                  "defaultRepresentationClassAsString": "string",
                  "flavorJavaFileListType": false,
                  "flavorRemoteObjectType": false,
                  "flavorSerializedObjectType": false,
                  "flavorTextType": false,
                  "mimeTypeSerializedObject": false,
                  "representationClassByteBuffer": false,
                  "representationClassCharBuffer": false,
                  "representationClassInputStream": false,
                  "representationClassReader": false,
                  "representationClassRemote": false,
                  "representationClassSerializable": false,
                  "primaryType": "string",
                  "subType": "string"
                }
              ],
              "preferredCommands": [
                {
                  "commandName": "string",
                  "commandClass": "string"
                }
              ],
              "allCommands": [
                {
                  "commandName": "string",
                  "commandClass": "string"
                }
              ]
            }
          }
        ]
      },
      "attribute": [
        {
          "attCode": "string",
          "attDesc": "string",
          "attVal": "string"
        }
      ],
      "gridOrgData": {
        "gridContact": {
          "addr": {
            "addr1": "string",
            "city": "string",
            "stateProv": "string",
            "postalCode": "string",
            "countryCode": {
              "countryCodeValue": "string"
            }
          }
        },
        "entityIdentifier": "string",
        "orgName": {
          "name": "string"
        }
      }
    },
    "statusType": {
      "statusCode": 0,
      "severity": "ERROR",
      "statusDesc": "string",
      "additionalStatus": [
        {
          "statusCode": 0,
          "severity": "ERROR",
          "statusDesc": "string"
        }
      ]
    },
    "note": "string",
    "alerts": [
      {
        "gridAlertId": "string",
        "gridAlertInfo": {
          "reportPDF": "string",
          "gridInquiryRec": {
            "gridInquiryId": "string",
            "gridInquiryInfo": {
              "portfolioMonitoring": false,
              "loadOnly": false,
              "globalSearch": false,
              "reporting": "string",
              "tracking": "string",
              "gridPersonPartyInfo": {
                "partyContext": {
                  "note": "string"
                },
                "pictures": {
                  "picture": [
                    {
                      "pictureTyp": "string",
                      "pictureData": {
                        "dataSource": {
                          "name": "string",
                          "inputStream": {},
                          "contentType": "string",
                          "outputStream": {}
                        },
                        "name": "string",
                        "inputStream": {},
                        "content": {},
                        "contentType": "string",
                        "outputStream": {},
                        "transferDataFlavors": [
                          {
                            "mimeType": "string",
                            "humanPresentableName": "string",
                            "defaultRepresentationClassAsString": "string",
                            "flavorJavaFileListType": false,
                            "flavorRemoteObjectType": false,
                            "flavorSerializedObjectType": false,
                            "flavorTextType": false,
                            "mimeTypeSerializedObject": false,
                            "representationClassByteBuffer": false,
                            "representationClassCharBuffer": false,
                            "representationClassInputStream": false,
                            "representationClassReader": false,
                            "representationClassRemote": false,
                            "representationClassSerializable": false,
                            "primaryType": "string",
                            "subType": "string"
                          }
                        ],
                        "preferredCommands": [
                          {
                            "commandName": "string",
                            "commandClass": "string"
                          }
                        ],
                        "allCommands": [
                          {
                            "commandName": "string",
                            "commandClass": "string"
                          }
                        ]
                      }
                    }
                  ]
                },
                "attribute": [
                  {
                    "attCode": "string",
                    "attDesc": "string",
                    "attVal": "string"
                  }
                ],
                "gridPersonData": {
                  "gridContact": {
                    "addr": {
                      "addr1": "string",
                      "city": "string",
                      "stateProv": "string",
                      "postalCode": "string",
                      "countryCode": {
                        "countryCodeValue": "string"
                      }
                    }
                  },
                  "entityIdentifier": "string",
                  "personName": {
                    "fullName": "string",
                    "familyName": "string",
                    "givenName": "string",
                    "middleName": "string"
                  }
                },
                "birthDt": "2021-06-30T12:35:40.929Z",
                "age": 0,
                "sex": "M"
              },
              "gridOrgPartyInfo": {
                "partyContext": {
                  "note": "string"
                },
                "pictures": {
                  "picture": [
                    {
                      "pictureTyp": "string",
                      "pictureData": {
                        "dataSource": {
                          "name": "string",
                          "inputStream": {},
                          "contentType": "string",
                          "outputStream": {}
                        },
                        "name": "string",
                        "inputStream": {},
                        "content": {},
                        "contentType": "string",
                        "outputStream": {},
                        "transferDataFlavors": [
                          {
                            "mimeType": "string",
                            "humanPresentableName": "string",
                            "defaultRepresentationClassAsString": "string",
                            "flavorJavaFileListType": false,
                            "flavorRemoteObjectType": false,
                            "flavorSerializedObjectType": false,
                            "flavorTextType": false,
                            "mimeTypeSerializedObject": false,
                            "representationClassByteBuffer": false,
                            "representationClassCharBuffer": false,
                            "representationClassInputStream": false,
                            "representationClassReader": false,
                            "representationClassRemote": false,
                            "representationClassSerializable": false,
                            "primaryType": "string",
                            "subType": "string"
                          }
                        ],
                        "preferredCommands": [
                          {
                            "commandName": "string",
                            "commandClass": "string"
                          }
                        ],
                        "allCommands": [
                          {
                            "commandName": "string",
                            "commandClass": "string"
                          }
                        ]
                      }
                    }
                  ]
                },
                "attribute": [
                  {
                    "attCode": "string",
                    "attDesc": "string",
                    "attVal": "string"
                  }
                ],
                "gridOrgData": {
                  "gridContact": {
                    "addr": {
                      "addr1": "string",
                      "city": "string",
                      "stateProv": "string",
                      "postalCode": "string",
                      "countryCode": {
                        "countryCodeValue": "string"
                      }
                    }
                  },
                  "entityIdentifier": "string",
                  "orgName": {
                    "name": "string"
                  }
                }
              },
              "note": "string"
            },
            "gridInquiryStatus": {
              "gridInquiryStatusCode": "COMPLETE",
              "statusDesc": "string",
              "effDt": "string"
            }
          },
          "alerts": {
            "alertDt": "string",
            "alertEntity": [
              {
                "matchScore": 0,
                "riskScore": 0,
                "cvip": "string",
                "entityId": 0,
                "entityTyp": "string",
                "entityName": "string",
                "source": {
                  "sourceName": "string",
                  "sourceURL": "string",
                  "entityDt": "2021-06-30T12:35:40.930Z",
                  "format": "string",
                  "headline": "string",
                  "publicationSource": "string",
                  "publisher": "string",
                  "sourceKy": "string"
                },
                "event": [
                  {
                    "category": {
                      "categoryCode": "string",
                      "categoryDesc": "string"
                    },
                    "eventDesc": "string",
                    "eventDt": "2021-06-30T12:35:40.930Z",
                    "subCategory": {
                      "categoryCode": "string",
                      "categoryDesc": "string"
                    },
                    "source": {
                      "sourceName": "string",
                      "sourceURL": "string",
                      "entityDt": "2021-06-30T12:35:40.930Z",
                      "format": "string",
                      "headline": "string",
                      "publicationSource": "string",
                      "publisher": "string",
                      "sourceKy": "string"
                    }
                  }
                ],
                "postAddr": [
                  {
                    "locatorTyp": "string",
                    "addr1": "string",
                    "addr2": "string",
                    "city": "string",
                    "stateProv": "string",
                    "postalCode": "string",
                    "countryCode": {
                      "countryCodeValue": "string"
                    },
                    "fromDt": "2021-06-30T12:35:40.930Z",
                    "toDt": "2021-06-30T12:35:40.930Z"
                  }
                ],
                "birthDt": [
                  "2021-06-30T12:35:40.930Z"
                ],
                "attribute": [
                  {
                    "attCode": "string",
                    "attDesc": "string",
                    "attVal": "string"
                  }
                ],
                "alertNote": "string",
                "sysId": "string",
                "rdcURL": "string",
                "alias": [
                  {
                    "aliasTyp": "string",
                    "aliasName": "string"
                  }
                ],
                "sources": {
                  "source": [
                    {
                      "sourceName": "string",
                      "sourceURL": "string",
                      "entityDt": "2021-06-30T12:35:40.930Z",
                      "format": "string",
                      "headline": "string",
                      "publicationSource": "string",
                      "publisher": "string",
                      "sourceKy": "string"
                    }
                  ]
                },
                "positions": {
                  "position": [
                    "string"
                  ]
                },
                "rels": {
                  "rel": [
                    {
                      "relDir": "string",
                      "relTyp": "string",
                      "sysId": "string",
                      "entityName": "string"
                    }
                  ]
                },
                "alertConfidence": 0
              }
            ],
            "nonReviewedAlertEntity": [
              {
                "matchScore": 0,
                "riskScore": 0,
                "cvip": "string",
                "entityId": 0,
                "entityTyp": "string",
                "entityName": "string",
                "source": {
                  "sourceName": "string",
                  "sourceURL": "string",
                  "entityDt": "2021-06-30T12:35:40.930Z",
                  "format": "string",
                  "headline": "string",
                  "publicationSource": "string",
                  "publisher": "string",
                  "sourceKy": "string"
                },
                "event": [
                  {
                    "category": {
                      "categoryCode": "string",
                      "categoryDesc": "string"
                    },
                    "eventDesc": "string",
                    "eventDt": "2021-06-30T12:35:40.930Z",
                    "subCategory": {
                      "categoryCode": "string",
                      "categoryDesc": "string"
                    },
                    "source": {
                      "sourceName": "string",
                      "sourceURL": "string",
                      "entityDt": "2021-06-30T12:35:40.930Z",
                      "format": "string",
                      "headline": "string",
                      "publicationSource": "string",
                      "publisher": "string",
                      "sourceKy": "string"
                    }
                  }
                ],
                "postAddr": [
                  {
                    "locatorTyp": "string",
                    "addr1": "string",
                    "addr2": "string",
                    "city": "string",
                    "stateProv": "string",
                    "postalCode": "string",
                    "countryCode": {
                      "countryCodeValue": "string"
                    },
                    "fromDt": "2021-06-30T12:35:40.930Z",
                    "toDt": "2021-06-30T12:35:40.930Z"
                  }
                ],
                "birthDt": [
                  "2021-06-30T12:35:40.930Z"
                ],
                "attribute": [
                  {
                    "attCode": "string",
                    "attDesc": "string",
                    "attVal": "string"
                  }
                ],
                "alertNote": "string",
                "sysId": "string",
                "rdcURL": "string",
                "alias": [
                  {
                    "aliasTyp": "string",
                    "aliasName": "string"
                  }
                ],
                "sources": {
                  "source": [
                    {
                      "sourceName": "string",
                      "sourceURL": "string",
                      "entityDt": "2021-06-30T12:35:40.930Z",
                      "format": "string",
                      "headline": "string",
                      "publicationSource": "string",
                      "publisher": "string",
                      "sourceKy": "string"
                    }
                  ]
                },
                "positions": {
                  "position": [
                    "string"
                  ]
                },
                "rels": {
                  "rel": [
                    {
                      "relDir": "string",
                      "relTyp": "string",
                      "sysId": "string",
                      "entityName": "string"
                    }
                  ]
                },
                "alertConfidence": 0
              }
            ],
            "clientDecisionedAlertEntity": [
              {
                "matchScore": 0,
                "riskScore": 0,
                "cvip": "string",
                "entityId": 0,
                "entityTyp": "string",
                "entityName": "string",
                "source": {
                  "sourceName": "string",
                  "sourceURL": "string",
                  "entityDt": "2021-06-30T12:35:40.930Z",
                  "format": "string",
                  "headline": "string",
                  "publicationSource": "string",
                  "publisher": "string",
                  "sourceKy": "string"
                },
                "event": [
                  {
                    "category": {
                      "categoryCode": "string",
                      "categoryDesc": "string"
                    },
                    "eventDesc": "string",
                    "eventDt": "2021-06-30T12:35:40.930Z",
                    "subCategory": {
                      "categoryCode": "string",
                      "categoryDesc": "string"
                    },
                    "source": {
                      "sourceName": "string",
                      "sourceURL": "string",
                      "entityDt": "2021-06-30T12:35:40.930Z",
                      "format": "string",
                      "headline": "string",
                      "publicationSource": "string",
                      "publisher": "string",
                      "sourceKy": "string"
                    }
                  }
                ],
                "postAddr": [
                  {
                    "locatorTyp": "string",
                    "addr1": "string",
                    "addr2": "string",
                    "city": "string",
                    "stateProv": "string",
                    "postalCode": "string",
                    "countryCode": {
                      "countryCodeValue": "string"
                    },
                    "fromDt": "2021-06-30T12:35:40.930Z",
                    "toDt": "2021-06-30T12:35:40.930Z"
                  }
                ],
                "birthDt": [
                  "2021-06-30T12:35:40.930Z"
                ],
                "attribute": [
                  {
                    "attCode": "string",
                    "attDesc": "string",
                    "attVal": "string"
                  }
                ],
                "alertNote": "string",
                "sysId": "string",
                "rdcURL": "string",
                "alias": [
                  {
                    "aliasTyp": "string",
                    "aliasName": "string"
                  }
                ],
                "sources": {
                  "source": [
                    {
                      "sourceName": "string",
                      "sourceURL": "string",
                      "entityDt": "2021-06-30T12:35:40.930Z",
                      "format": "string",
                      "headline": "string",
                      "publicationSource": "string",
                      "publisher": "string",
                      "sourceKy": "string"
                    }
                  ]
                },
                "positions": {
                  "position": [
                    "string"
                  ]
                },
                "rels": {
                  "rel": [
                    {
                      "relDir": "string",
                      "relTyp": "string",
                      "sysId": "string",
                      "entityName": "string"
                    }
                  ]
                },
                "alertConfidence": 0,
                "clientDecisioningReason": {
                  "reasonCode": "string",
                  "reasonDescription": "string"
                }
              }
            ],
            "alertIlistEntry": [
              {
                "matchScore": 0,
                "personIlistInfo": {
                  "ilistTrackingId": "string",
                  "ilistEntryId": 0,
                  "ilist": {
                    "ilistId": 0,
                    "name": "string",
                    "description": "string",
                    "source": [
                      {
                        "sourceName": "string",
                        "sourceURL": "string",
                        "entityDt": "2021-06-30T12:35:40.930Z",
                        "format": "string",
                        "headline": "string",
                        "publicationSource": "string",
                        "publisher": "string",
                        "sourceKy": "string"
                      }
                    ]
                  },
                  "ilistEvent": {
                    "category": {
                      "categoryCode": "string",
                      "categoryDesc": "string"
                    },
                    "eventDesc": "string",
                    "eventDt": "2021-06-30T12:35:40.930Z",
                    "subCategory": {
                      "categoryCode": "string",
                      "categoryDesc": "string"
                    },
                    "source": {
                      "sourceName": "string",
                      "sourceURL": "string",
                      "entityDt": "2021-06-30T12:35:40.930Z",
                      "format": "string",
                      "headline": "string",
                      "publicationSource": "string",
                      "publisher": "string",
                      "sourceKy": "string"
                    },
                    "endDate": "2021-06-30T12:35:40.930Z"
                  },
                  "alertNote": "string",
                  "alias": [
                    {
                      "aliasTyp": "string",
                      "aliasName": "string"
                    }
                  ],
                  "rdcId": [
                    {
                      "rdcIdTyp": "string",
                      "rdcIdVal": "string"
                    }
                  ],
                  "additionalInfo": [
                    {
                      "info": "string"
                    }
                  ],
                  "entryRule": [
                    {
                      "entryRuleDescription": "string"
                    }
                  ],
                  "postAddr": [
                    {
                      "locatorTyp": "string",
                      "addr1": "string",
                      "addr2": "string",
                      "city": "string",
                      "stateProv": "string",
                      "postalCode": "string",
                      "countryCode": {
                        "countryCodeValue": "string"
                      },
                      "fromDt": "2021-06-30T12:35:40.930Z",
                      "toDt": "2021-06-30T12:35:40.930Z"
                    }
                  ],
                  "birthDt": [
                    "2021-06-30T12:35:40.930Z"
                  ],
                  "personId": [
                    {
                      "driversLicenseOrPassportOrGenericPersonId": [
                        {}
                      ]
                    }
                  ],
                  "personName": {
                    "fullName": "string",
                    "familyName": "string",
                    "givenName": "string",
                    "middleName": "string"
                  }
                },
                "orgIlistInfo": {
                  "ilistTrackingId": "string",
                  "ilistEntryId": 0,
                  "ilist": {
                    "ilistId": 0,
                    "name": "string",
                    "description": "string",
                    "source": [
                      {
                        "sourceName": "string",
                        "sourceURL": "string",
                        "entityDt": "2021-06-30T12:35:40.930Z",
                        "format": "string",
                        "headline": "string",
                        "publicationSource": "string",
                        "publisher": "string",
                        "sourceKy": "string"
                      }
                    ]
                  },
                  "ilistEvent": {
                    "category": {
                      "categoryCode": "string",
                      "categoryDesc": "string"
                    },
                    "eventDesc": "string",
                    "eventDt": "2021-06-30T12:35:40.930Z",
                    "subCategory": {
                      "categoryCode": "string",
                      "categoryDesc": "string"
                    },
                    "source": {
                      "sourceName": "string",
                      "sourceURL": "string",
                      "entityDt": "2021-06-30T12:35:40.930Z",
                      "format": "string",
                      "headline": "string",
                      "publicationSource": "string",
                      "publisher": "string",
                      "sourceKy": "string"
                    },
                    "endDate": "2021-06-30T12:35:40.930Z"
                  },
                  "alertNote": "string",
                  "alias": [
                    {
                      "aliasTyp": "string",
                      "aliasName": "string"
                    }
                  ],
                  "rdcId": [
                    {
                      "rdcIdTyp": "string",
                      "rdcIdVal": "string"
                    }
                  ],
                  "additionalInfo": [
                    {
                      "info": "string"
                    }
                  ],
                  "entryRule": [
                    {
                      "entryRuleDescription": "string"
                    }
                  ],
                  "postAddr": [
                    {
                      "locatorTyp": "string",
                      "addr1": "string",
                      "addr2": "string",
                      "city": "string",
                      "stateProv": "string",
                      "postalCode": "string",
                      "countryCode": {
                        "countryCodeValue": "string"
                      },
                      "fromDt": "2021-06-30T12:35:40.930Z",
                      "toDt": "2021-06-30T12:35:40.930Z"
                    }
                  ],
                  "orgId": [
                    {
                      "genericOrgId": [
                        {
                          "genericIdNbr": "string",
                          "genericIdTyp": "SSN",
                          "genericIdIssueDt": "2021-06-30T12:35:40.930Z",
                          "genericIdExpDt": "2021-06-30T12:35:40.930Z",
                          "genericIdCountryCode": {
                            "countryCodeValue": "string"
                          }
                        }
                      ]
                    }
                  ],
                  "name": "string"
                },
                "countryIlistInfo": {
                  "ilistTrackingId": "string",
                  "ilistEntryId": 0,
                  "ilist": {
                    "ilistId": 0,
                    "name": "string",
                    "description": "string",
                    "source": [
                      {
                        "sourceName": "string",
                        "sourceURL": "string",
                        "entityDt": "2021-06-30T12:35:40.930Z",
                        "format": "string",
                        "headline": "string",
                        "publicationSource": "string",
                        "publisher": "string",
                        "sourceKy": "string"
                      }
                    ]
                  },
                  "ilistEvent": {
                    "category": {
                      "categoryCode": "string",
                      "categoryDesc": "string"
                    },
                    "eventDesc": "string",
                    "eventDt": "2021-06-30T12:35:40.930Z",
                    "subCategory": {
                      "categoryCode": "string",
                      "categoryDesc": "string"
                    },
                    "source": {
                      "sourceName": "string",
                      "sourceURL": "string",
                      "entityDt": "2021-06-30T12:35:40.930Z",
                      "format": "string",
                      "headline": "string",
                      "publicationSource": "string",
                      "publisher": "string",
                      "sourceKy": "string"
                    },
                    "endDate": "2021-06-30T12:35:40.930Z"
                  },
                  "alertNote": "string",
                  "alias": [
                    {
                      "aliasTyp": "string",
                      "aliasName": "string"
                    }
                  ],
                  "rdcId": [
                    {
                      "rdcIdTyp": "string",
                      "rdcIdVal": "string"
                    }
                  ],
                  "additionalInfo": [
                    {
                      "info": "string"
                    }
                  ],
                  "entryRule": [
                    {
                      "entryRuleDescription": "string"
                    }
                  ],
                  "name": "string",
                  "shortName": "string"
                }
              }
            ],
            "clientDecisionedAlertIlistEntry": [
              {
                "matchScore": 0,
                "personIlistInfo": {
                  "ilistTrackingId": "string",
                  "ilistEntryId": 0,
                  "ilist": {
                    "ilistId": 0,
                    "name": "string",
                    "description": "string",
                    "source": [
                      {
                        "sourceName": "string",
                        "sourceURL": "string",
                        "entityDt": "2021-06-30T12:35:40.930Z",
                        "format": "string",
                        "headline": "string",
                        "publicationSource": "string",
                        "publisher": "string",
                        "sourceKy": "string"
                      }
                    ]
                  },
                  "ilistEvent": {
                    "category": {
                      "categoryCode": "string",
                      "categoryDesc": "string"
                    },
                    "eventDesc": "string",
                    "eventDt": "2021-06-30T12:35:40.930Z",
                    "subCategory": {
                      "categoryCode": "string",
                      "categoryDesc": "string"
                    },
                    "source": {
                      "sourceName": "string",
                      "sourceURL": "string",
                      "entityDt": "2021-06-30T12:35:40.930Z",
                      "format": "string",
                      "headline": "string",
                      "publicationSource": "string",
                      "publisher": "string",
                      "sourceKy": "string"
                    },
                    "endDate": "2021-06-30T12:35:40.930Z"
                  },
                  "alertNote": "string",
                  "alias": [
                    {
                      "aliasTyp": "string",
                      "aliasName": "string"
                    }
                  ],
                  "rdcId": [
                    {
                      "rdcIdTyp": "string",
                      "rdcIdVal": "string"
                    }
                  ],
                  "additionalInfo": [
                    {
                      "info": "string"
                    }
                  ],
                  "entryRule": [
                    {
                      "entryRuleDescription": "string"
                    }
                  ],
                  "postAddr": [
                    {
                      "locatorTyp": "string",
                      "addr1": "string",
                      "addr2": "string",
                      "city": "string",
                      "stateProv": "string",
                      "postalCode": "string",
                      "countryCode": {
                        "countryCodeValue": "string"
                      },
                      "fromDt": "2021-06-30T12:35:40.930Z",
                      "toDt": "2021-06-30T12:35:40.930Z"
                    }
                  ],
                  "birthDt": [
                    "2021-06-30T12:35:40.930Z"
                  ],
                  "personId": [
                    {
                      "driversLicenseOrPassportOrGenericPersonId": [
                        {}
                      ]
                    }
                  ],
                  "personName": {
                    "fullName": "string",
                    "familyName": "string",
                    "givenName": "string",
                    "middleName": "string"
                  }
                },
                "orgIlistInfo": {
                  "ilistTrackingId": "string",
                  "ilistEntryId": 0,
                  "ilist": {
                    "ilistId": 0,
                    "name": "string",
                    "description": "string",
                    "source": [
                      {
                        "sourceName": "string",
                        "sourceURL": "string",
                        "entityDt": "2021-06-30T12:35:40.930Z",
                        "format": "string",
                        "headline": "string",
                        "publicationSource": "string",
                        "publisher": "string",
                        "sourceKy": "string"
                      }
                    ]
                  },
                  "ilistEvent": {
                    "category": {
                      "categoryCode": "string",
                      "categoryDesc": "string"
                    },
                    "eventDesc": "string",
                    "eventDt": "2021-06-30T12:35:40.930Z",
                    "subCategory": {
                      "categoryCode": "string",
                      "categoryDesc": "string"
                    },
                    "source": {
                      "sourceName": "string",
                      "sourceURL": "string",
                      "entityDt": "2021-06-30T12:35:40.930Z",
                      "format": "string",
                      "headline": "string",
                      "publicationSource": "string",
                      "publisher": "string",
                      "sourceKy": "string"
                    },
                    "endDate": "2021-06-30T12:35:40.930Z"
                  },
                  "alertNote": "string",
                  "alias": [
                    {
                      "aliasTyp": "string",
                      "aliasName": "string"
                    }
                  ],
                  "rdcId": [
                    {
                      "rdcIdTyp": "string",
                      "rdcIdVal": "string"
                    }
                  ],
                  "additionalInfo": [
                    {
                      "info": "string"
                    }
                  ],
                  "entryRule": [
                    {
                      "entryRuleDescription": "string"
                    }
                  ],
                  "postAddr": [
                    {
                      "locatorTyp": "string",
                      "addr1": "string",
                      "addr2": "string",
                      "city": "string",
                      "stateProv": "string",
                      "postalCode": "string",
                      "countryCode": {
                        "countryCodeValue": "string"
                      },
                      "fromDt": "2021-06-30T12:35:40.930Z",
                      "toDt": "2021-06-30T12:35:40.930Z"
                    }
                  ],
                  "orgId": [
                    {
                      "genericOrgId": [
                        {
                          "genericIdNbr": "string",
                          "genericIdTyp": "SSN",
                          "genericIdIssueDt": "2021-06-30T12:35:40.930Z",
                          "genericIdExpDt": "2021-06-30T12:35:40.930Z",
                          "genericIdCountryCode": {
                            "countryCodeValue": "string"
                          }
                        }
                      ]
                    }
                  ],
                  "name": "string"
                },
                "countryIlistInfo": {
                  "ilistTrackingId": "string",
                  "ilistEntryId": 0,
                  "ilist": {
                    "ilistId": 0,
                    "name": "string",
                    "description": "string",
                    "source": [
                      {
                        "sourceName": "string",
                        "sourceURL": "string",
                        "entityDt": "2021-06-30T12:35:40.930Z",
                        "format": "string",
                        "headline": "string",
                        "publicationSource": "string",
                        "publisher": "string",
                        "sourceKy": "string"
                      }
                    ]
                  },
                  "ilistEvent": {
                    "category": {
                      "categoryCode": "string",
                      "categoryDesc": "string"
                    },
                    "eventDesc": "string",
                    "eventDt": "2021-06-30T12:35:40.930Z",
                    "subCategory": {
                      "categoryCode": "string",
                      "categoryDesc": "string"
                    },
                    "source": {
                      "sourceName": "string",
                      "sourceURL": "string",
                      "entityDt": "2021-06-30T12:35:40.930Z",
                      "format": "string",
                      "headline": "string",
                      "publicationSource": "string",
                      "publisher": "string",
                      "sourceKy": "string"
                    },
                    "endDate": "2021-06-30T12:35:40.930Z"
                  },
                  "alertNote": "string",
                  "alias": [
                    {
                      "aliasTyp": "string",
                      "aliasName": "string"
                    }
                  ],
                  "rdcId": [
                    {
                      "rdcIdTyp": "string",
                      "rdcIdVal": "string"
                    }
                  ],
                  "additionalInfo": [
                    {
                      "info": "string"
                    }
                  ],
                  "entryRule": [
                    {
                      "entryRuleDescription": "string"
                    }
                  ],
                  "name": "string",
                  "shortName": "string"
                },
                "clientDecisioningReason": {
                  "reasonCode": "string",
                  "reasonDescription": "string"
                }
              }
            ],
            "nonReviewedAlertIlistEntry": [
              {
                "matchScore": 0,
                "personIlistInfo": {
                  "ilistTrackingId": "string",
                  "ilistEntryId": 0,
                  "ilist": {
                    "ilistId": 0,
                    "name": "string",
                    "description": "string",
                    "source": [
                      {
                        "sourceName": "string",
                        "sourceURL": "string",
                        "entityDt": "2021-06-30T12:35:40.930Z",
                        "format": "string",
                        "headline": "string",
                        "publicationSource": "string",
                        "publisher": "string",
                        "sourceKy": "string"
                      }
                    ]
                  },
                  "ilistEvent": {
                    "category": {
                      "categoryCode": "string",
                      "categoryDesc": "string"
                    },
                    "eventDesc": "string",
                    "eventDt": "2021-06-30T12:35:40.930Z",
                    "subCategory": {
                      "categoryCode": "string",
                      "categoryDesc": "string"
                    },
                    "source": {
                      "sourceName": "string",
                      "sourceURL": "string",
                      "entityDt": "2021-06-30T12:35:40.930Z",
                      "format": "string",
                      "headline": "string",
                      "publicationSource": "string",
                      "publisher": "string",
                      "sourceKy": "string"
                    },
                    "endDate": "2021-06-30T12:35:40.930Z"
                  },
                  "alertNote": "string",
                  "alias": [
                    {
                      "aliasTyp": "string",
                      "aliasName": "string"
                    }
                  ],
                  "rdcId": [
                    {
                      "rdcIdTyp": "string",
                      "rdcIdVal": "string"
                    }
                  ],
                  "additionalInfo": [
                    {
                      "info": "string"
                    }
                  ],
                  "entryRule": [
                    {
                      "entryRuleDescription": "string"
                    }
                  ],
                  "postAddr": [
                    {
                      "locatorTyp": "string",
                      "addr1": "string",
                      "addr2": "string",
                      "city": "string",
                      "stateProv": "string",
                      "postalCode": "string",
                      "countryCode": {
                        "countryCodeValue": "string"
                      },
                      "fromDt": "2021-06-30T12:35:40.930Z",
                      "toDt": "2021-06-30T12:35:40.930Z"
                    }
                  ],
                  "birthDt": [
                    "2021-06-30T12:35:40.930Z"
                  ],
                  "personId": [
                    {
                      "driversLicenseOrPassportOrGenericPersonId": [
                        {}
                      ]
                    }
                  ],
                  "personName": {
                    "fullName": "string",
                    "familyName": "string",
                    "givenName": "string",
                    "middleName": "string"
                  }
                },
                "orgIlistInfo": {
                  "ilistTrackingId": "string",
                  "ilistEntryId": 0,
                  "ilist": {
                    "ilistId": 0,
                    "name": "string",
                    "description": "string",
                    "source": [
                      {
                        "sourceName": "string",
                        "sourceURL": "string",
                        "entityDt": "2021-06-30T12:35:40.930Z",
                        "format": "string",
                        "headline": "string",
                        "publicationSource": "string",
                        "publisher": "string",
                        "sourceKy": "string"
                      }
                    ]
                  },
                  "ilistEvent": {
                    "category": {
                      "categoryCode": "string",
                      "categoryDesc": "string"
                    },
                    "eventDesc": "string",
                    "eventDt": "2021-06-30T12:35:40.930Z",
                    "subCategory": {
                      "categoryCode": "string",
                      "categoryDesc": "string"
                    },
                    "source": {
                      "sourceName": "string",
                      "sourceURL": "string",
                      "entityDt": "2021-06-30T12:35:40.930Z",
                      "format": "string",
                      "headline": "string",
                      "publicationSource": "string",
                      "publisher": "string",
                      "sourceKy": "string"
                    },
                    "endDate": "2021-06-30T12:35:40.930Z"
                  },
                  "alertNote": "string",
                  "alias": [
                    {
                      "aliasTyp": "string",
                      "aliasName": "string"
                    }
                  ],
                  "rdcId": [
                    {
                      "rdcIdTyp": "string",
                      "rdcIdVal": "string"
                    }
                  ],
                  "additionalInfo": [
                    {
                      "info": "string"
                    }
                  ],
                  "entryRule": [
                    {
                      "entryRuleDescription": "string"
                    }
                  ],
                  "postAddr": [
                    {
                      "locatorTyp": "string",
                      "addr1": "string",
                      "addr2": "string",
                      "city": "string",
                      "stateProv": "string",
                      "postalCode": "string",
                      "countryCode": {
                        "countryCodeValue": "string"
                      },
                      "fromDt": "2021-06-30T12:35:40.930Z",
                      "toDt": "2021-06-30T12:35:40.930Z"
                    }
                  ],
                  "orgId": [
                    {
                      "genericOrgId": [
                        {
                          "genericIdNbr": "string",
                          "genericIdTyp": "SSN",
                          "genericIdIssueDt": "2021-06-30T12:35:40.930Z",
                          "genericIdExpDt": "2021-06-30T12:35:40.930Z",
                          "genericIdCountryCode": {
                            "countryCodeValue": "string"
                          }
                        }
                      ]
                    }
                  ],
                  "name": "string"
                },
                "countryIlistInfo": {
                  "ilistTrackingId": "string",
                  "ilistEntryId": 0,
                  "ilist": {
                    "ilistId": 0,
                    "name": "string",
                    "description": "string",
                    "source": [
                      {
                        "sourceName": "string",
                        "sourceURL": "string",
                        "entityDt": "2021-06-30T12:35:40.930Z",
                        "format": "string",
                        "headline": "string",
                        "publicationSource": "string",
                        "publisher": "string",
                        "sourceKy": "string"
                      }
                    ]
                  },
                  "ilistEvent": {
                    "category": {
                      "categoryCode": "string",
                      "categoryDesc": "string"
                    },
                    "eventDesc": "string",
                    "eventDt": "2021-06-30T12:35:40.930Z",
                    "subCategory": {
                      "categoryCode": "string",
                      "categoryDesc": "string"
                    },
                    "source": {
                      "sourceName": "string",
                      "sourceURL": "string",
                      "entityDt": "2021-06-30T12:35:40.930Z",
                      "format": "string",
                      "headline": "string",
                      "publicationSource": "string",
                      "publisher": "string",
                      "sourceKy": "string"
                    },
                    "endDate": "2021-06-30T12:35:40.930Z"
                  },
                  "alertNote": "string",
                  "alias": [
                    {
                      "aliasTyp": "string",
                      "aliasName": "string"
                    }
                  ],
                  "rdcId": [
                    {
                      "rdcIdTyp": "string",
                      "rdcIdVal": "string"
                    }
                  ],
                  "additionalInfo": [
                    {
                      "info": "string"
                    }
                  ],
                  "entryRule": [
                    {
                      "entryRuleDescription": "string"
                    }
                  ],
                  "name": "string",
                  "shortName": "string"
                }
              }
            ]
          },
          "clientDecisioningNote": [
            {
              "note": "string",
              "createdUser": "string",
              "createdDateTime": "string"
            }
          ]
        },
        "gridAlertStatus": {
          "gridAlertStatusCode": "COMPLETE",
          "statusDesc": "string",
          "effDt": "string"
        }
      }
    ],
    "targetFirmNumber": "string"
  },
  "status": {
    "code": 0,
    "type": "ERROR",
    "description": "string",
    "additionalResponseStatuses": [
      {
        "type": "ERROR",
        "description": "string",
        "code": 0
      }
    ]
  }
};
var rls = [
        {
            dataType: 'number', 
            expectedValue: 34
        },
        {
            dataType: 'number', 
            expectedValue: 344
        },
    ];

let loopProps = function(obj, rules) {
        for(const property in obj) {
            document.write(`${property}: ${obj[property]}, typeof: ${typeof obj[property]} <br />`);
            check(obj[property], rules);
        }
}
let loopArr = function(objRes, rules) { 
    for (var i = 0; i < objRes.length; i++) {
        var obj = objRes[i];
        document.write(` <br /> <br />looping array item: ${JSON.stringify(obj)} <br />`)
        loopProps(obj, rules);
    }
}
let loopRules = function(property, rules) {
    for (var y = 0; y < rules.length; y++) {
        var rule = rules[y];
        document.write(`Checking Rule: ${JSON.stringify(rule)} <br />`)
        var propType = typeof property
        if (propType === rule.dataType) {
            document.write(`${propType} == ${rule.dataType} <br />`);
            document.write(`Check Value: ${property} == Rule Expected Value: ${rule.expectedValue} <br />`);
        }
    }
}
let check = function(objRes, rules) {
    let objResType = typeof objRes;
    switch (objResType) {
        case 'object':
            if (Array.isArray(objRes)) {
                loopArr(objRes, rules);
            } else {
                loopProps(objRes, rules);
            }
            break;
        case 'string': 
            loopRules(objRes, rules);
            break;
        case 'number': 
            loopRules(objRes, rules);
            break;
    }
}

check(obj, rls)

</script>
<br />
<br />
<br />
<br />
```javascript 
    /// check the incoming data
    let check = function(objRes, rules) {
        let objResType = typeof objRes;
        switch (objResType) {
            case 'object':
                if (Array.isArray(objRes)) {
                    document.write('looping array <br />')
                    loopArr(objRes, rules);
                } else {
                    loopProps(objRes, rules);
                }
                break;
            case 'string': 
                loopRules(objRes, rules);
                break;
            case 'number': 
                loopRules(objRes, rules);
                break;
        }
    }
```

```javascript
    // setup each of the loops
    let loopProps = function(obj, rules) {
        for(const property in obj) {
            document.write(`${property}: ${obj[property]}, typeof: ${typeof obj[property]} <br />`);
            check(obj[property], rules);
            }
    }
    let loopArr = function(objRes, rules) { 
        for (var i = 0; i < objRes.length; i++) {
            var obj = objRes[i];
            document.write(`looping array item: ${JSON.stringify(obj)} <br />`)
            loopProps(obj, rules);
        }
    }
    let loopRules = function(property, rules) {
        for (var y = 0; y < rules.length; y++) {
            var rule = rules[y];
            document.write(`Checking Rule: ${JSON.stringify(rule)} <br />`)
            var propType = typeof property
            if (propType === rule.dataType) {
                document.write(`${propType} == ${rule.dataType} <br />`);
                document.write(`Check Value: ${property} == Rule Expected Value: ${rule.expectedValue} <br />`);
            }
        }
    }
```

```javascript
    {
    "data": {
        "id": "string",
        "status": "COMPLETE",
        "reviewStatus": "ALERT",
        "portfolioMonitoring": false,
        "loadOnly": false,
        "globalSearch": false,
        "reporting": "string",
        "tracking": "string",
        "gridPersonPartyInfo": {
        "partyContext": {
            "note": "string"
        },
        "pictures": {
            "picture": [
            {
                "pictureTyp": "string",
                "pictureData": {
                "dataSource": {
                    "name": "string",
                    "inputStream": {},
                    "contentType": "string",
                    "outputStream": {}
                },
                "name": "string",
                "inputStream": {},
                "content": {},
                "contentType": "string",
                "outputStream": {},
                "transferDataFlavors": [
                    {
                    "mimeType": "string",
                    "humanPresentableName": "string",
                    "defaultRepresentationClassAsString": "string",
                    "flavorJavaFileListType": false,
                    "flavorRemoteObjectType": false,
                    "flavorSerializedObjectType": false,
                    "flavorTextType": false,
                    "mimeTypeSerializedObject": false,
                    "representationClassByteBuffer": false,
                    "representationClassCharBuffer": false,
                    "representationClassInputStream": false,
                    "representationClassReader": false,
                    "representationClassRemote": false,
                    "representationClassSerializable": false,
                    "primaryType": "string",
                    "subType": "string"
                    }
                ],
                "preferredCommands": [
                    {
                    "commandName": "string",
                    "commandClass": "string"
                    }
                ],
                "allCommands": [
                    {
                    "commandName": "string",
                    "commandClass": "string"
                    }
                ]
                }
            }
            ]
        },
        "attribute": [
            {
            "attCode": "string",
            "attDesc": "string",
            "attVal": "string"
            }
        ],
        "gridPersonData": {
            "gridContact": {
            "addr": {
                "addr1": "string",
                "city": "string",
                "stateProv": "string",
                "postalCode": "string",
                "countryCode": {
                "countryCodeValue": "string"
                }
            }
            },
            "entityIdentifier": "string",
            "personName": {
            "fullName": "string",
            "familyName": "string",
            "givenName": "string",
            "middleName": "string"
            }
        },
        "birthDt": "2021-06-30T12:35:40.929Z",
        "age": 0,
        "sex": "M"
        },
        "gridOrgPartyInfo": {
        "partyContext": {
            "note": "string"
        },
        "pictures": {
            "picture": [
            {
                "pictureTyp": "string",
                "pictureData": {
                "dataSource": {
                    "name": "string",
                    "inputStream": {},
                    "contentType": "string",
                    "outputStream": {}
                },
                "name": "string",
                "inputStream": {},
                "content": {},
                "contentType": "string",
                "outputStream": {},
                "transferDataFlavors": [
                    {
                    "mimeType": "string",
                    "humanPresentableName": "string",
                    "defaultRepresentationClassAsString": "string",
                    "flavorJavaFileListType": false,
                    "flavorRemoteObjectType": false,
                    "flavorSerializedObjectType": false,
                    "flavorTextType": false,
                    "mimeTypeSerializedObject": false,
                    "representationClassByteBuffer": false,
                    "representationClassCharBuffer": false,
                    "representationClassInputStream": false,
                    "representationClassReader": false,
                    "representationClassRemote": false,
                    "representationClassSerializable": false,
                    "primaryType": "string",
                    "subType": "string"
                    }
                ],
                "preferredCommands": [
                    {
                    "commandName": "string",
                    "commandClass": "string"
                    }
                ],
                "allCommands": [
                    {
                    "commandName": "string",
                    "commandClass": "string"
                    }
                ]
                }
            }
            ]
        },
        "attribute": [
            {
            "attCode": "string",
            "attDesc": "string",
            "attVal": "string"
            }
        ],
        "gridOrgData": {
            "gridContact": {
            "addr": {
                "addr1": "string",
                "city": "string",
                "stateProv": "string",
                "postalCode": "string",
                "countryCode": {
                "countryCodeValue": "string"
                }
            }
            },
            "entityIdentifier": "string",
            "orgName": {
            "name": "string"
            }
        }
        },
        "statusType": {
        "statusCode": 0,
        "severity": "ERROR",
        "statusDesc": "string",
        "additionalStatus": [
            {
            "statusCode": 0,
            "severity": "ERROR",
            "statusDesc": "string"
            }
        ]
        },
        "note": "string",
        "alerts": [
        {
            "gridAlertId": "string",
            "gridAlertInfo": {
            "reportPDF": "string",
            "gridInquiryRec": {
                "gridInquiryId": "string",
                "gridInquiryInfo": {
                "portfolioMonitoring": false,
                "loadOnly": false,
                "globalSearch": false,
                "reporting": "string",
                "tracking": "string",
                "gridPersonPartyInfo": {
                    "partyContext": {
                    "note": "string"
                    },
                    "pictures": {
                    "picture": [
                        {
                        "pictureTyp": "string",
                        "pictureData": {
                            "dataSource": {
                            "name": "string",
                            "inputStream": {},
                            "contentType": "string",
                            "outputStream": {}
                            },
                            "name": "string",
                            "inputStream": {},
                            "content": {},
                            "contentType": "string",
                            "outputStream": {},
                            "transferDataFlavors": [
                            {
                                "mimeType": "string",
                                "humanPresentableName": "string",
                                "defaultRepresentationClassAsString": "string",
                                "flavorJavaFileListType": false,
                                "flavorRemoteObjectType": false,
                                "flavorSerializedObjectType": false,
                                "flavorTextType": false,
                                "mimeTypeSerializedObject": false,
                                "representationClassByteBuffer": false,
                                "representationClassCharBuffer": false,
                                "representationClassInputStream": false,
                                "representationClassReader": false,
                                "representationClassRemote": false,
                                "representationClassSerializable": false,
                                "primaryType": "string",
                                "subType": "string"
                            }
                            ],
                            "preferredCommands": [
                            {
                                "commandName": "string",
                                "commandClass": "string"
                            }
                            ],
                            "allCommands": [
                            {
                                "commandName": "string",
                                "commandClass": "string"
                            }
                            ]
                        }
                        }
                    ]
                    },
                    "attribute": [
                    {
                        "attCode": "string",
                        "attDesc": "string",
                        "attVal": "string"
                    }
                    ],
                    "gridPersonData": {
                    "gridContact": {
                        "addr": {
                        "addr1": "string",
                        "city": "string",
                        "stateProv": "string",
                        "postalCode": "string",
                        "countryCode": {
                            "countryCodeValue": "string"
                        }
                        }
                    },
                    "entityIdentifier": "string",
                    "personName": {
                        "fullName": "string",
                        "familyName": "string",
                        "givenName": "string",
                        "middleName": "string"
                    }
                    },
                    "birthDt": "2021-06-30T12:35:40.929Z",
                    "age": 0,
                    "sex": "M"
                },
                "gridOrgPartyInfo": {
                    "partyContext": {
                    "note": "string"
                    },
                    "pictures": {
                    "picture": [
                        {
                        "pictureTyp": "string",
                        "pictureData": {
                            "dataSource": {
                            "name": "string",
                            "inputStream": {},
                            "contentType": "string",
                            "outputStream": {}
                            },
                            "name": "string",
                            "inputStream": {},
                            "content": {},
                            "contentType": "string",
                            "outputStream": {},
                            "transferDataFlavors": [
                            {
                                "mimeType": "string",
                                "humanPresentableName": "string",
                                "defaultRepresentationClassAsString": "string",
                                "flavorJavaFileListType": false,
                                "flavorRemoteObjectType": false,
                                "flavorSerializedObjectType": false,
                                "flavorTextType": false,
                                "mimeTypeSerializedObject": false,
                                "representationClassByteBuffer": false,
                                "representationClassCharBuffer": false,
                                "representationClassInputStream": false,
                                "representationClassReader": false,
                                "representationClassRemote": false,
                                "representationClassSerializable": false,
                                "primaryType": "string",
                                "subType": "string"
                            }
                            ],
                            "preferredCommands": [
                            {
                                "commandName": "string",
                                "commandClass": "string"
                            }
                            ],
                            "allCommands": [
                            {
                                "commandName": "string",
                                "commandClass": "string"
                            }
                            ]
                        }
                        }
                    ]
                    },
                    "attribute": [
                    {
                        "attCode": "string",
                        "attDesc": "string",
                        "attVal": "string"
                    }
                    ],
                    "gridOrgData": {
                    "gridContact": {
                        "addr": {
                        "addr1": "string",
                        "city": "string",
                        "stateProv": "string",
                        "postalCode": "string",
                        "countryCode": {
                            "countryCodeValue": "string"
                        }
                        }
                    },
                    "entityIdentifier": "string",
                    "orgName": {
                        "name": "string"
                    }
                    }
                },
                "note": "string"
                },
                "gridInquiryStatus": {
                "gridInquiryStatusCode": "COMPLETE",
                "statusDesc": "string",
                "effDt": "string"
                }
            },
            "alerts": {
                "alertDt": "string",
                "alertEntity": [
                {
                    "matchScore": 0,
                    "riskScore": 0,
                    "cvip": "string",
                    "entityId": 0,
                    "entityTyp": "string",
                    "entityName": "string",
                    "source": {
                    "sourceName": "string",
                    "sourceURL": "string",
                    "entityDt": "2021-06-30T12:35:40.930Z",
                    "format": "string",
                    "headline": "string",
                    "publicationSource": "string",
                    "publisher": "string",
                    "sourceKy": "string"
                    },
                    "event": [
                    {
                        "category": {
                        "categoryCode": "string",
                        "categoryDesc": "string"
                        },
                        "eventDesc": "string",
                        "eventDt": "2021-06-30T12:35:40.930Z",
                        "subCategory": {
                        "categoryCode": "string",
                        "categoryDesc": "string"
                        },
                        "source": {
                        "sourceName": "string",
                        "sourceURL": "string",
                        "entityDt": "2021-06-30T12:35:40.930Z",
                        "format": "string",
                        "headline": "string",
                        "publicationSource": "string",
                        "publisher": "string",
                        "sourceKy": "string"
                        }
                    }
                    ],
                    "postAddr": [
                    {
                        "locatorTyp": "string",
                        "addr1": "string",
                        "addr2": "string",
                        "city": "string",
                        "stateProv": "string",
                        "postalCode": "string",
                        "countryCode": {
                        "countryCodeValue": "string"
                        },
                        "fromDt": "2021-06-30T12:35:40.930Z",
                        "toDt": "2021-06-30T12:35:40.930Z"
                    }
                    ],
                    "birthDt": [
                    "2021-06-30T12:35:40.930Z"
                    ],
                    "attribute": [
                    {
                        "attCode": "string",
                        "attDesc": "string",
                        "attVal": "string"
                    }
                    ],
                    "alertNote": "string",
                    "sysId": "string",
                    "rdcURL": "string",
                    "alias": [
                    {
                        "aliasTyp": "string",
                        "aliasName": "string"
                    }
                    ],
                    "sources": {
                    "source": [
                        {
                        "sourceName": "string",
                        "sourceURL": "string",
                        "entityDt": "2021-06-30T12:35:40.930Z",
                        "format": "string",
                        "headline": "string",
                        "publicationSource": "string",
                        "publisher": "string",
                        "sourceKy": "string"
                        }
                    ]
                    },
                    "positions": {
                    "position": [
                        "string"
                    ]
                    },
                    "rels": {
                    "rel": [
                        {
                        "relDir": "string",
                        "relTyp": "string",
                        "sysId": "string",
                        "entityName": "string"
                        }
                    ]
                    },
                    "alertConfidence": 0
                }
                ],
                "nonReviewedAlertEntity": [
                {
                    "matchScore": 0,
                    "riskScore": 0,
                    "cvip": "string",
                    "entityId": 0,
                    "entityTyp": "string",
                    "entityName": "string",
                    "source": {
                    "sourceName": "string",
                    "sourceURL": "string",
                    "entityDt": "2021-06-30T12:35:40.930Z",
                    "format": "string",
                    "headline": "string",
                    "publicationSource": "string",
                    "publisher": "string",
                    "sourceKy": "string"
                    },
                    "event": [
                    {
                        "category": {
                        "categoryCode": "string",
                        "categoryDesc": "string"
                        },
                        "eventDesc": "string",
                        "eventDt": "2021-06-30T12:35:40.930Z",
                        "subCategory": {
                        "categoryCode": "string",
                        "categoryDesc": "string"
                        },
                        "source": {
                        "sourceName": "string",
                        "sourceURL": "string",
                        "entityDt": "2021-06-30T12:35:40.930Z",
                        "format": "string",
                        "headline": "string",
                        "publicationSource": "string",
                        "publisher": "string",
                        "sourceKy": "string"
                        }
                    }
                    ],
                    "postAddr": [
                    {
                        "locatorTyp": "string",
                        "addr1": "string",
                        "addr2": "string",
                        "city": "string",
                        "stateProv": "string",
                        "postalCode": "string",
                        "countryCode": {
                        "countryCodeValue": "string"
                        },
                        "fromDt": "2021-06-30T12:35:40.930Z",
                        "toDt": "2021-06-30T12:35:40.930Z"
                    }
                    ],
                    "birthDt": [
                    "2021-06-30T12:35:40.930Z"
                    ],
                    "attribute": [
                    {
                        "attCode": "string",
                        "attDesc": "string",
                        "attVal": "string"
                    }
                    ],
                    "alertNote": "string",
                    "sysId": "string",
                    "rdcURL": "string",
                    "alias": [
                    {
                        "aliasTyp": "string",
                        "aliasName": "string"
                    }
                    ],
                    "sources": {
                    "source": [
                        {
                        "sourceName": "string",
                        "sourceURL": "string",
                        "entityDt": "2021-06-30T12:35:40.930Z",
                        "format": "string",
                        "headline": "string",
                        "publicationSource": "string",
                        "publisher": "string",
                        "sourceKy": "string"
                        }
                    ]
                    },
                    "positions": {
                    "position": [
                        "string"
                    ]
                    },
                    "rels": {
                    "rel": [
                        {
                        "relDir": "string",
                        "relTyp": "string",
                        "sysId": "string",
                        "entityName": "string"
                        }
                    ]
                    },
                    "alertConfidence": 0
                }
                ],
                "clientDecisionedAlertEntity": [
                {
                    "matchScore": 0,
                    "riskScore": 0,
                    "cvip": "string",
                    "entityId": 0,
                    "entityTyp": "string",
                    "entityName": "string",
                    "source": {
                    "sourceName": "string",
                    "sourceURL": "string",
                    "entityDt": "2021-06-30T12:35:40.930Z",
                    "format": "string",
                    "headline": "string",
                    "publicationSource": "string",
                    "publisher": "string",
                    "sourceKy": "string"
                    },
                    "event": [
                    {
                        "category": {
                        "categoryCode": "string",
                        "categoryDesc": "string"
                        },
                        "eventDesc": "string",
                        "eventDt": "2021-06-30T12:35:40.930Z",
                        "subCategory": {
                        "categoryCode": "string",
                        "categoryDesc": "string"
                        },
                        "source": {
                        "sourceName": "string",
                        "sourceURL": "string",
                        "entityDt": "2021-06-30T12:35:40.930Z",
                        "format": "string",
                        "headline": "string",
                        "publicationSource": "string",
                        "publisher": "string",
                        "sourceKy": "string"
                        }
                    }
                    ],
                    "postAddr": [
                    {
                        "locatorTyp": "string",
                        "addr1": "string",
                        "addr2": "string",
                        "city": "string",
                        "stateProv": "string",
                        "postalCode": "string",
                        "countryCode": {
                        "countryCodeValue": "string"
                        },
                        "fromDt": "2021-06-30T12:35:40.930Z",
                        "toDt": "2021-06-30T12:35:40.930Z"
                    }
                    ],
                    "birthDt": [
                    "2021-06-30T12:35:40.930Z"
                    ],
                    "attribute": [
                    {
                        "attCode": "string",
                        "attDesc": "string",
                        "attVal": "string"
                    }
                    ],
                    "alertNote": "string",
                    "sysId": "string",
                    "rdcURL": "string",
                    "alias": [
                    {
                        "aliasTyp": "string",
                        "aliasName": "string"
                    }
                    ],
                    "sources": {
                    "source": [
                        {
                        "sourceName": "string",
                        "sourceURL": "string",
                        "entityDt": "2021-06-30T12:35:40.930Z",
                        "format": "string",
                        "headline": "string",
                        "publicationSource": "string",
                        "publisher": "string",
                        "sourceKy": "string"
                        }
                    ]
                    },
                    "positions": {
                    "position": [
                        "string"
                    ]
                    },
                    "rels": {
                    "rel": [
                        {
                        "relDir": "string",
                        "relTyp": "string",
                        "sysId": "string",
                        "entityName": "string"
                        }
                    ]
                    },
                    "alertConfidence": 0,
                    "clientDecisioningReason": {
                    "reasonCode": "string",
                    "reasonDescription": "string"
                    }
                }
                ],
                "alertIlistEntry": [
                {
                    "matchScore": 0,
                    "personIlistInfo": {
                    "ilistTrackingId": "string",
                    "ilistEntryId": 0,
                    "ilist": {
                        "ilistId": 0,
                        "name": "string",
                        "description": "string",
                        "source": [
                        {
                            "sourceName": "string",
                            "sourceURL": "string",
                            "entityDt": "2021-06-30T12:35:40.930Z",
                            "format": "string",
                            "headline": "string",
                            "publicationSource": "string",
                            "publisher": "string",
                            "sourceKy": "string"
                        }
                        ]
                    },
                    "ilistEvent": {
                        "category": {
                        "categoryCode": "string",
                        "categoryDesc": "string"
                        },
                        "eventDesc": "string",
                        "eventDt": "2021-06-30T12:35:40.930Z",
                        "subCategory": {
                        "categoryCode": "string",
                        "categoryDesc": "string"
                        },
                        "source": {
                        "sourceName": "string",
                        "sourceURL": "string",
                        "entityDt": "2021-06-30T12:35:40.930Z",
                        "format": "string",
                        "headline": "string",
                        "publicationSource": "string",
                        "publisher": "string",
                        "sourceKy": "string"
                        },
                        "endDate": "2021-06-30T12:35:40.930Z"
                    },
                    "alertNote": "string",
                    "alias": [
                        {
                        "aliasTyp": "string",
                        "aliasName": "string"
                        }
                    ],
                    "rdcId": [
                        {
                        "rdcIdTyp": "string",
                        "rdcIdVal": "string"
                        }
                    ],
                    "additionalInfo": [
                        {
                        "info": "string"
                        }
                    ],
                    "entryRule": [
                        {
                        "entryRuleDescription": "string"
                        }
                    ],
                    "postAddr": [
                        {
                        "locatorTyp": "string",
                        "addr1": "string",
                        "addr2": "string",
                        "city": "string",
                        "stateProv": "string",
                        "postalCode": "string",
                        "countryCode": {
                            "countryCodeValue": "string"
                        },
                        "fromDt": "2021-06-30T12:35:40.930Z",
                        "toDt": "2021-06-30T12:35:40.930Z"
                        }
                    ],
                    "birthDt": [
                        "2021-06-30T12:35:40.930Z"
                    ],
                    "personId": [
                        {
                        "driversLicenseOrPassportOrGenericPersonId": [
                            {}
                        ]
                        }
                    ],
                    "personName": {
                        "fullName": "string",
                        "familyName": "string",
                        "givenName": "string",
                        "middleName": "string"
                    }
                    },
                    "orgIlistInfo": {
                    "ilistTrackingId": "string",
                    "ilistEntryId": 0,
                    "ilist": {
                        "ilistId": 0,
                        "name": "string",
                        "description": "string",
                        "source": [
                        {
                            "sourceName": "string",
                            "sourceURL": "string",
                            "entityDt": "2021-06-30T12:35:40.930Z",
                            "format": "string",
                            "headline": "string",
                            "publicationSource": "string",
                            "publisher": "string",
                            "sourceKy": "string"
                        }
                        ]
                    },
                    "ilistEvent": {
                        "category": {
                        "categoryCode": "string",
                        "categoryDesc": "string"
                        },
                        "eventDesc": "string",
                        "eventDt": "2021-06-30T12:35:40.930Z",
                        "subCategory": {
                        "categoryCode": "string",
                        "categoryDesc": "string"
                        },
                        "source": {
                        "sourceName": "string",
                        "sourceURL": "string",
                        "entityDt": "2021-06-30T12:35:40.930Z",
                        "format": "string",
                        "headline": "string",
                        "publicationSource": "string",
                        "publisher": "string",
                        "sourceKy": "string"
                        },
                        "endDate": "2021-06-30T12:35:40.930Z"
                    },
                    "alertNote": "string",
                    "alias": [
                        {
                        "aliasTyp": "string",
                        "aliasName": "string"
                        }
                    ],
                    "rdcId": [
                        {
                        "rdcIdTyp": "string",
                        "rdcIdVal": "string"
                        }
                    ],
                    "additionalInfo": [
                        {
                        "info": "string"
                        }
                    ],
                    "entryRule": [
                        {
                        "entryRuleDescription": "string"
                        }
                    ],
                    "postAddr": [
                        {
                        "locatorTyp": "string",
                        "addr1": "string",
                        "addr2": "string",
                        "city": "string",
                        "stateProv": "string",
                        "postalCode": "string",
                        "countryCode": {
                            "countryCodeValue": "string"
                        },
                        "fromDt": "2021-06-30T12:35:40.930Z",
                        "toDt": "2021-06-30T12:35:40.930Z"
                        }
                    ],
                    "orgId": [
                        {
                        "genericOrgId": [
                            {
                            "genericIdNbr": "string",
                            "genericIdTyp": "SSN",
                            "genericIdIssueDt": "2021-06-30T12:35:40.930Z",
                            "genericIdExpDt": "2021-06-30T12:35:40.930Z",
                            "genericIdCountryCode": {
                                "countryCodeValue": "string"
                            }
                            }
                        ]
                        }
                    ],
                    "name": "string"
                    },
                    "countryIlistInfo": {
                    "ilistTrackingId": "string",
                    "ilistEntryId": 0,
                    "ilist": {
                        "ilistId": 0,
                        "name": "string",
                        "description": "string",
                        "source": [
                        {
                            "sourceName": "string",
                            "sourceURL": "string",
                            "entityDt": "2021-06-30T12:35:40.930Z",
                            "format": "string",
                            "headline": "string",
                            "publicationSource": "string",
                            "publisher": "string",
                            "sourceKy": "string"
                        }
                        ]
                    },
                    "ilistEvent": {
                        "category": {
                        "categoryCode": "string",
                        "categoryDesc": "string"
                        },
                        "eventDesc": "string",
                        "eventDt": "2021-06-30T12:35:40.930Z",
                        "subCategory": {
                        "categoryCode": "string",
                        "categoryDesc": "string"
                        },
                        "source": {
                        "sourceName": "string",
                        "sourceURL": "string",
                        "entityDt": "2021-06-30T12:35:40.930Z",
                        "format": "string",
                        "headline": "string",
                        "publicationSource": "string",
                        "publisher": "string",
                        "sourceKy": "string"
                        },
                        "endDate": "2021-06-30T12:35:40.930Z"
                    },
                    "alertNote": "string",
                    "alias": [
                        {
                        "aliasTyp": "string",
                        "aliasName": "string"
                        }
                    ],
                    "rdcId": [
                        {
                        "rdcIdTyp": "string",
                        "rdcIdVal": "string"
                        }
                    ],
                    "additionalInfo": [
                        {
                        "info": "string"
                        }
                    ],
                    "entryRule": [
                        {
                        "entryRuleDescription": "string"
                        }
                    ],
                    "name": "string",
                    "shortName": "string"
                    }
                }
                ],
                "clientDecisionedAlertIlistEntry": [
                {
                    "matchScore": 0,
                    "personIlistInfo": {
                    "ilistTrackingId": "string",
                    "ilistEntryId": 0,
                    "ilist": {
                        "ilistId": 0,
                        "name": "string",
                        "description": "string",
                        "source": [
                        {
                            "sourceName": "string",
                            "sourceURL": "string",
                            "entityDt": "2021-06-30T12:35:40.930Z",
                            "format": "string",
                            "headline": "string",
                            "publicationSource": "string",
                            "publisher": "string",
                            "sourceKy": "string"
                        }
                        ]
                    },
                    "ilistEvent": {
                        "category": {
                        "categoryCode": "string",
                        "categoryDesc": "string"
                        },
                        "eventDesc": "string",
                        "eventDt": "2021-06-30T12:35:40.930Z",
                        "subCategory": {
                        "categoryCode": "string",
                        "categoryDesc": "string"
                        },
                        "source": {
                        "sourceName": "string",
                        "sourceURL": "string",
                        "entityDt": "2021-06-30T12:35:40.930Z",
                        "format": "string",
                        "headline": "string",
                        "publicationSource": "string",
                        "publisher": "string",
                        "sourceKy": "string"
                        },
                        "endDate": "2021-06-30T12:35:40.930Z"
                    },
                    "alertNote": "string",
                    "alias": [
                        {
                        "aliasTyp": "string",
                        "aliasName": "string"
                        }
                    ],
                    "rdcId": [
                        {
                        "rdcIdTyp": "string",
                        "rdcIdVal": "string"
                        }
                    ],
                    "additionalInfo": [
                        {
                        "info": "string"
                        }
                    ],
                    "entryRule": [
                        {
                        "entryRuleDescription": "string"
                        }
                    ],
                    "postAddr": [
                        {
                        "locatorTyp": "string",
                        "addr1": "string",
                        "addr2": "string",
                        "city": "string",
                        "stateProv": "string",
                        "postalCode": "string",
                        "countryCode": {
                            "countryCodeValue": "string"
                        },
                        "fromDt": "2021-06-30T12:35:40.930Z",
                        "toDt": "2021-06-30T12:35:40.930Z"
                        }
                    ],
                    "birthDt": [
                        "2021-06-30T12:35:40.930Z"
                    ],
                    "personId": [
                        {
                        "driversLicenseOrPassportOrGenericPersonId": [
                            {}
                        ]
                        }
                    ],
                    "personName": {
                        "fullName": "string",
                        "familyName": "string",
                        "givenName": "string",
                        "middleName": "string"
                    }
                    },
                    "orgIlistInfo": {
                    "ilistTrackingId": "string",
                    "ilistEntryId": 0,
                    "ilist": {
                        "ilistId": 0,
                        "name": "string",
                        "description": "string",
                        "source": [
                        {
                            "sourceName": "string",
                            "sourceURL": "string",
                            "entityDt": "2021-06-30T12:35:40.930Z",
                            "format": "string",
                            "headline": "string",
                            "publicationSource": "string",
                            "publisher": "string",
                            "sourceKy": "string"
                        }
                        ]
                    },
                    "ilistEvent": {
                        "category": {
                        "categoryCode": "string",
                        "categoryDesc": "string"
                        },
                        "eventDesc": "string",
                        "eventDt": "2021-06-30T12:35:40.930Z",
                        "subCategory": {
                        "categoryCode": "string",
                        "categoryDesc": "string"
                        },
                        "source": {
                        "sourceName": "string",
                        "sourceURL": "string",
                        "entityDt": "2021-06-30T12:35:40.930Z",
                        "format": "string",
                        "headline": "string",
                        "publicationSource": "string",
                        "publisher": "string",
                        "sourceKy": "string"
                        },
                        "endDate": "2021-06-30T12:35:40.930Z"
                    },
                    "alertNote": "string",
                    "alias": [
                        {
                        "aliasTyp": "string",
                        "aliasName": "string"
                        }
                    ],
                    "rdcId": [
                        {
                        "rdcIdTyp": "string",
                        "rdcIdVal": "string"
                        }
                    ],
                    "additionalInfo": [
                        {
                        "info": "string"
                        }
                    ],
                    "entryRule": [
                        {
                        "entryRuleDescription": "string"
                        }
                    ],
                    "postAddr": [
                        {
                        "locatorTyp": "string",
                        "addr1": "string",
                        "addr2": "string",
                        "city": "string",
                        "stateProv": "string",
                        "postalCode": "string",
                        "countryCode": {
                            "countryCodeValue": "string"
                        },
                        "fromDt": "2021-06-30T12:35:40.930Z",
                        "toDt": "2021-06-30T12:35:40.930Z"
                        }
                    ],
                    "orgId": [
                        {
                        "genericOrgId": [
                            {
                            "genericIdNbr": "string",
                            "genericIdTyp": "SSN",
                            "genericIdIssueDt": "2021-06-30T12:35:40.930Z",
                            "genericIdExpDt": "2021-06-30T12:35:40.930Z",
                            "genericIdCountryCode": {
                                "countryCodeValue": "string"
                            }
                            }
                        ]
                        }
                    ],
                    "name": "string"
                    },
                    "countryIlistInfo": {
                    "ilistTrackingId": "string",
                    "ilistEntryId": 0,
                    "ilist": {
                        "ilistId": 0,
                        "name": "string",
                        "description": "string",
                        "source": [
                        {
                            "sourceName": "string",
                            "sourceURL": "string",
                            "entityDt": "2021-06-30T12:35:40.930Z",
                            "format": "string",
                            "headline": "string",
                            "publicationSource": "string",
                            "publisher": "string",
                            "sourceKy": "string"
                        }
                        ]
                    },
                    "ilistEvent": {
                        "category": {
                        "categoryCode": "string",
                        "categoryDesc": "string"
                        },
                        "eventDesc": "string",
                        "eventDt": "2021-06-30T12:35:40.930Z",
                        "subCategory": {
                        "categoryCode": "string",
                        "categoryDesc": "string"
                        },
                        "source": {
                        "sourceName": "string",
                        "sourceURL": "string",
                        "entityDt": "2021-06-30T12:35:40.930Z",
                        "format": "string",
                        "headline": "string",
                        "publicationSource": "string",
                        "publisher": "string",
                        "sourceKy": "string"
                        },
                        "endDate": "2021-06-30T12:35:40.930Z"
                    },
                    "alertNote": "string",
                    "alias": [
                        {
                        "aliasTyp": "string",
                        "aliasName": "string"
                        }
                    ],
                    "rdcId": [
                        {
                        "rdcIdTyp": "string",
                        "rdcIdVal": "string"
                        }
                    ],
                    "additionalInfo": [
                        {
                        "info": "string"
                        }
                    ],
                    "entryRule": [
                        {
                        "entryRuleDescription": "string"
                        }
                    ],
                    "name": "string",
                    "shortName": "string"
                    },
                    "clientDecisioningReason": {
                    "reasonCode": "string",
                    "reasonDescription": "string"
                    }
                }
                ],
                "nonReviewedAlertIlistEntry": [
                {
                    "matchScore": 0,
                    "personIlistInfo": {
                    "ilistTrackingId": "string",
                    "ilistEntryId": 0,
                    "ilist": {
                        "ilistId": 0,
                        "name": "string",
                        "description": "string",
                        "source": [
                        {
                            "sourceName": "string",
                            "sourceURL": "string",
                            "entityDt": "2021-06-30T12:35:40.930Z",
                            "format": "string",
                            "headline": "string",
                            "publicationSource": "string",
                            "publisher": "string",
                            "sourceKy": "string"
                        }
                        ]
                    },
                    "ilistEvent": {
                        "category": {
                        "categoryCode": "string",
                        "categoryDesc": "string"
                        },
                        "eventDesc": "string",
                        "eventDt": "2021-06-30T12:35:40.930Z",
                        "subCategory": {
                        "categoryCode": "string",
                        "categoryDesc": "string"
                        },
                        "source": {
                        "sourceName": "string",
                        "sourceURL": "string",
                        "entityDt": "2021-06-30T12:35:40.930Z",
                        "format": "string",
                        "headline": "string",
                        "publicationSource": "string",
                        "publisher": "string",
                        "sourceKy": "string"
                        },
                        "endDate": "2021-06-30T12:35:40.930Z"
                    },
                    "alertNote": "string",
                    "alias": [
                        {
                        "aliasTyp": "string",
                        "aliasName": "string"
                        }
                    ],
                    "rdcId": [
                        {
                        "rdcIdTyp": "string",
                        "rdcIdVal": "string"
                        }
                    ],
                    "additionalInfo": [
                        {
                        "info": "string"
                        }
                    ],
                    "entryRule": [
                        {
                        "entryRuleDescription": "string"
                        }
                    ],
                    "postAddr": [
                        {
                        "locatorTyp": "string",
                        "addr1": "string",
                        "addr2": "string",
                        "city": "string",
                        "stateProv": "string",
                        "postalCode": "string",
                        "countryCode": {
                            "countryCodeValue": "string"
                        },
                        "fromDt": "2021-06-30T12:35:40.930Z",
                        "toDt": "2021-06-30T12:35:40.930Z"
                        }
                    ],
                    "birthDt": [
                        "2021-06-30T12:35:40.930Z"
                    ],
                    "personId": [
                        {
                        "driversLicenseOrPassportOrGenericPersonId": [
                            {}
                        ]
                        }
                    ],
                    "personName": {
                        "fullName": "string",
                        "familyName": "string",
                        "givenName": "string",
                        "middleName": "string"
                    }
                    },
                    "orgIlistInfo": {
                    "ilistTrackingId": "string",
                    "ilistEntryId": 0,
                    "ilist": {
                        "ilistId": 0,
                        "name": "string",
                        "description": "string",
                        "source": [
                        {
                            "sourceName": "string",
                            "sourceURL": "string",
                            "entityDt": "2021-06-30T12:35:40.930Z",
                            "format": "string",
                            "headline": "string",
                            "publicationSource": "string",
                            "publisher": "string",
                            "sourceKy": "string"
                        }
                        ]
                    },
                    "ilistEvent": {
                        "category": {
                        "categoryCode": "string",
                        "categoryDesc": "string"
                        },
                        "eventDesc": "string",
                        "eventDt": "2021-06-30T12:35:40.930Z",
                        "subCategory": {
                        "categoryCode": "string",
                        "categoryDesc": "string"
                        },
                        "source": {
                        "sourceName": "string",
                        "sourceURL": "string",
                        "entityDt": "2021-06-30T12:35:40.930Z",
                        "format": "string",
                        "headline": "string",
                        "publicationSource": "string",
                        "publisher": "string",
                        "sourceKy": "string"
                        },
                        "endDate": "2021-06-30T12:35:40.930Z"
                    },
                    "alertNote": "string",
                    "alias": [
                        {
                        "aliasTyp": "string",
                        "aliasName": "string"
                        }
                    ],
                    "rdcId": [
                        {
                        "rdcIdTyp": "string",
                        "rdcIdVal": "string"
                        }
                    ],
                    "additionalInfo": [
                        {
                        "info": "string"
                        }
                    ],
                    "entryRule": [
                        {
                        "entryRuleDescription": "string"
                        }
                    ],
                    "postAddr": [
                        {
                        "locatorTyp": "string",
                        "addr1": "string",
                        "addr2": "string",
                        "city": "string",
                        "stateProv": "string",
                        "postalCode": "string",
                        "countryCode": {
                            "countryCodeValue": "string"
                        },
                        "fromDt": "2021-06-30T12:35:40.930Z",
                        "toDt": "2021-06-30T12:35:40.930Z"
                        }
                    ],
                    "orgId": [
                        {
                        "genericOrgId": [
                            {
                            "genericIdNbr": "string",
                            "genericIdTyp": "SSN",
                            "genericIdIssueDt": "2021-06-30T12:35:40.930Z",
                            "genericIdExpDt": "2021-06-30T12:35:40.930Z",
                            "genericIdCountryCode": {
                                "countryCodeValue": "string"
                            }
                            }
                        ]
                        }
                    ],
                    "name": "string"
                    },
                    "countryIlistInfo": {
                    "ilistTrackingId": "string",
                    "ilistEntryId": 0,
                    "ilist": {
                        "ilistId": 0,
                        "name": "string",
                        "description": "string",
                        "source": [
                        {
                            "sourceName": "string",
                            "sourceURL": "string",
                            "entityDt": "2021-06-30T12:35:40.930Z",
                            "format": "string",
                            "headline": "string",
                            "publicationSource": "string",
                            "publisher": "string",
                            "sourceKy": "string"
                        }
                        ]
                    },
                    "ilistEvent": {
                        "category": {
                        "categoryCode": "string",
                        "categoryDesc": "string"
                        },
                        "eventDesc": "string",
                        "eventDt": "2021-06-30T12:35:40.930Z",
                        "subCategory": {
                        "categoryCode": "string",
                        "categoryDesc": "string"
                        },
                        "source": {
                        "sourceName": "string",
                        "sourceURL": "string",
                        "entityDt": "2021-06-30T12:35:40.930Z",
                        "format": "string",
                        "headline": "string",
                        "publicationSource": "string",
                        "publisher": "string",
                        "sourceKy": "string"
                        },
                        "endDate": "2021-06-30T12:35:40.930Z"
                    },
                    "alertNote": "string",
                    "alias": [
                        {
                        "aliasTyp": "string",
                        "aliasName": "string"
                        }
                    ],
                    "rdcId": [
                        {
                        "rdcIdTyp": "string",
                        "rdcIdVal": "string"
                        }
                    ],
                    "additionalInfo": [
                        {
                        "info": "string"
                        }
                    ],
                    "entryRule": [
                        {
                        "entryRuleDescription": "string"
                        }
                    ],
                    "name": "string",
                    "shortName": "string"
                    }
                }
                ]
            },
            "clientDecisioningNote": [
                {
                "note": "string",
                "createdUser": "string",
                "createdDateTime": "string"
                }
            ]
            },
            "gridAlertStatus": {
            "gridAlertStatusCode": "COMPLETE",
            "statusDesc": "string",
            "effDt": "string"
            }
        }
        ],
        "targetFirmNumber": "string"
    },
    "status": {
        "code": 0,
        "type": "ERROR",
        "description": "string",
        "additionalResponseStatuses": [
        {
            "type": "ERROR",
            "description": "string",
            "code": 0
        }
        ]
    }
    }
```