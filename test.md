# Request Data Arguments

Each example is a Bash `-d` argument containing a JSON request payload.

## 01. 

```bash
-d '{
  "common": {
    "key_info": {
      "so_id": "9000000000001",
      "so_link_target_id": "TST001"
    },
    "order_info": {
      "service_type_cd": "001",
      "order_type_cd": "001"
    }
  },
  "extension": {
    "add_info": {
      "subscriber_id": "CAF9000000001",
      "resource_id": null
    },
    "detail_info": {
      "item1": "ALE900000000000001",
      "item2": "00",
      "item3": "TEST0001",
      "item4": "001",
      "item5": "100002",
      "item6": "T01",
      "item7": null,
      "item8": "9001",
      "item9": "01",
      "item10": "01",
      "item11": "01",
      "item12": null,
      "item13": null,
      "item14": null
    }
  }
}'
```

## 02.

```bash
-d '{
  "common": {
    "key_info": {
      "so_id": "9000000000002",
      "so_link_target_id": "TST001"
    },
    "order_info": {
      "service_type_cd": "001",
      "order_type_cd": "002"
    }
  },
  "extension": {
    "add_info": {
      "subscriber_id": null,
      "resource_id": "9000000002"
    },
    "detail_info": {
      "item1": "ALE900000000000002",
      "item2": "0"
    }
  }
}'
```

## 03.

```bash
-d '{
  "common": {
    "key_info": {
      "so_id": "9000000000003",
      "so_link_target_id": "TST001"
    },
    "order_info": {
      "service_type_cd": "001",
      "order_type_cd": "004"
    }
  },
  "extension": {
    "add_info": {
      "subscriber_id": "CAF9000000003",
      "resource_id": null
    },
    "detail_info": {
      "item1": "ALE900000000000003",
      "item2": "00",
      "item3": "TEST0001",
      "item4": "001",
      "item5": "100002",
      "item6": "T01",
      "item7": null,
      "item8": "9001",
      "item9": "01",
      "item10": "01",
      "item11": "01",
      "item12": null,
      "item13": null,
      "item14": null,
      "item15": "9000000103"
    }
  }
}'
```

## 04.

```bash
-d '{
  "common": {
    "key_info": {
      "so_id": "9000000000004",
      "so_link_target_id": "TST001"
    },
    "order_info": {
      "service_type_cd": "001",
      "order_type_cd": "005"
    }
  },
  "extension": {
    "add_info": {
      "subscriber_id": "CAF9000000004",
      "resource_id": "9000000004"
    },
    "detail_info": {
      "item1": "ALE900000000000004",
      "item2": "0",
      "item3": "0"
    }
  }
}'
```

## 05.

```bash
-d '{
  "common": {
    "key_info": {
      "so_id": "9000000000005",
      "so_link_target_id": "TST001"
    },
    "order_info": {
      "service_type_cd": "001",
      "order_type_cd": "006"
    }
  },
  "extension": {
    "add_info": {
      "subscriber_id": "CAF9000000005",
      "resource_id": "9000000005"
    },
    "detail_info": {
      "item1": "SAE900000000000005",
      "item2": null,
      "item3": "100002"
    }
  }
}'
```

## 06. 

```bash
-d '{
  "common": {
    "key_info": {
      "so_id": "9000000000006",
      "so_link_target_id": "TST001"
    },
    "order_info": {
      "service_type_cd": "011",
      "order_type_cd": "001"
    }
  },
  "extension": {
    "add_info": {
      "subscriber_id": null,
      "resource_id": null
    },
    "detail_info": {
      "item1": "SWE900000000000006",
      "item2": "TEST0001",
      "item3": "001",
      "item4": "200003",
      "item5": "T01",
      "item6": "9001",
      "item7": "01",
      "item8": "01",
      "item9": "01",
      "item10": "SWH9000000000006",
      "item11": null,
      "item12": null
    }
  }
}'
```

## 07.

```bash
-d '{
  "common": {
    "key_info": {
      "so_id": "9000000000007",
      "so_link_target_id": "TST001"
    },
    "order_info": {
      "service_type_cd": "011",
      "order_type_cd": "002"
    }
  },
  "extension": {
    "add_info": {
      "subscriber_id": null,
      "resource_id": null
    },
    "detail_info": {
      "item1": "SWE900000000000007",
      "item2": "TEST0001",
      "item3": "001",
      "item4": "200003",
      "item5": "SWH9000000000007",
      "item6": "0"
    }
  }
}'
```

## 08.

```bash
-d '{
  "common": {
    "key_info": {
      "so_id": "9000000000008",
      "so_link_target_id": "990008"
    },
    "order_info": {
      "service_type_cd": "201",
      "order_type_cd": "001"
    }
  },
  "extension": {
    "add_info": {
      "subscriber_id": null,
      "resource_id": null
    },
    "detail_info": {
      "item1": "ALE900000000000008",
      "item2": "ZZTEST08",
      "item3": "002",
      "item4": "100001",
      "item5": null,
      "item6": "0",
      "item7": "0",
      "item8": null,
      "item9": "T08",
      "item10": "1008",
      "item11": "01",
      "item12": "02",
      "item13": "03",
      "item14": "00",
      "item15": null,
      "item16": null
    }
  }
}'
```

## 09. 

```bash
-d '{
  "common": {
    "key_info": {
      "so_id": "9000000000009",
      "so_link_target_id": "990009"
    },
    "order_info": {
      "service_type_cd": "201",
      "order_type_cd": "002"
    }
  },
  "extension": {
    "add_info": {
      "subscriber_id": null,
      "resource_id": "9000000009"
    },
    "detail_info": {
      "item1": "ALE900000000000009",
      "item2": "0"
    }
  }
}'
```

## 10. 

```bash
-d '{
  "common": {
    "key_info": {
      "so_id": "9000000000010",
      "so_link_target_id": "990010"
    },
    "order_info": {
      "service_type_cd": "201",
      "order_type_cd": "004"
    }
  },
  "extension": {
    "add_info": {
      "subscriber_id": null,
      "resource_id": null
    },
    "detail_info": {
      "item1": "BAS900000000000010",
      "item2": "00",
      "item3": null,
      "item4": "ZZTEST10",
      "item5": "002",
      "item6": "100001",
      "item7": "T10",
      "item8": "1010",
      "item9": "01",
      "item10": "02",
      "item11": "03",
      "item12": null,
      "item13": null,
      "item14": null,
      "item15": "0",
      "item16": "9000000010",
      "item17": "COP9000000000010",
      "item18": "0"
    }
  }
}'
```

## 11. 

```bash
-d '{
  "common": {
    "key_info": {
      "so_id": "9000000000011",
      "so_link_target_id": "990011"
    },
    "order_info": {
      "service_type_cd": "201",
      "order_type_cd": "005"
    }
  },
  "extension": {
    "add_info": {
      "subscriber_id": null,
      "resource_id": "9000000011"
    },
    "detail_info": {
      "item1": "BAS900000000000011",
      "item2": "COP9000000000011",
      "item3": "0",
      "item4": "0"
    }
  }
}'
```

## 12. 

```bash
-d '{
  "common": {
    "key_info": {
      "so_id": "9000000000012",
      "so_link_target_id": "990012"
    },
    "order_info": {
      "service_type_cd": "211",
      "order_type_cd": "001"
    }
  },
  "extension": {
    "add_info": {
      "subscriber_id": null,
      "resource_id": null
    },
    "detail_info": {
      "item1": "SWE900000000000012",
      "item2": "0",
      "item3": "ZZTEST12",
      "item4": "002",
      "item5": "200003",
      "item6": "T12",
      "item7": "1012",
      "item8": "01",
      "item9": "02",
      "item10": "01",
      "item11": "SWH9000000000012"
    }
  }
}'
```

## 13. 

```bash
-d '{
  "common": {
    "key_info": {
      "so_id": "9000000000013",
      "so_link_target_id": "990013"
    },
    "order_info": {
      "service_type_cd": "211",
      "order_type_cd": "002"
    }
  },
  "extension": {
    "add_info": {
      "subscriber_id": null,
      "resource_id": null
    },
    "detail_info": {
      "item1": "SWE900000000000013",
      "item2": "002",
      "item3": "200003",
      "item4": "SWH9000000000013",
      "item5": "0"
    }
  }
}'
```

## 14.

```bash
-d '{
  "common": {
    "key_info": {
      "so_id": "9000000000014",
      "so_link_target_id": "TST001"
    },
    "order_info": {
      "service_type_cd": "021",
      "order_type_cd": "001"
    }
  },
  "extension": {
    "add_info": {
      "subscriber_id": "CAF9000000008",
      "resource_id": "9000000008"
    },
    "detail_info": {
      "item1": "TVT900000000000008"
    }
  }
}'
```

## 15.

```bash
-d '{
  "common": {
    "key_info": {
      "so_id": "9000000000015",
      "so_link_target_id": "TST001"
    },
    "order_info": {
      "service_type_cd": "022",
      "order_type_cd": "001"
    }
  },
  "extension": {
    "add_info": {
      "subscriber_id": "CAF9000000009",
      "resource_id": "9000000009"
    },
    "detail_info": {
      "item1": "P2P900000000000009",
      "item2": "1",
      "item3": null
    }
  }
}'
```

## 16. 

```bash
-d '{
  "common": {
    "key_info": {
      "so_id": "9000000000016",
      "so_link_target_id": "TST001"
    },
    "order_info": {
      "service_type_cd": "022",
      "order_type_cd": "003"
    }
  },
  "extension": {
    "add_info": {
      "subscriber_id": "CAF9000000010",
      "resource_id": "9000000010"
    },
    "detail_info": {
      "item1": "P2P900000000000010",
      "item2": "1",
      "item3": null
    }
  }
}'
```

## 17. 

```bash
-d '{
  "common": {
    "key_info": {
      "so_id": "9000000000017",
      "so_link_target_id": "TST001"
    },
    "order_info": {
      "service_type_cd": "022",
      "order_type_cd": "002"
    }
  },
  "extension": {
    "add_info": {
      "subscriber_id": "CAF9000000011",
      "resource_id": "9000000011"
    },
    "detail_info": {
      "item1": "P2P900000000000011",
      "item2": "1",
      "item3": null
    }
  }
}'
```

## 18.

```bash
-d '{
  "common": {
    "key_info": {
      "so_id": "9000000000018",
      "so_link_target_id": "TST001"
    },
    "order_info": {
      "service_type_cd": "050",
      "order_type_cd": "001"
    }
  },
  "extension": {
    "add_info": {
      "subscriber_id": "CAF9000000000012",
      "resource_id": "9000000012"
    },
    "detail_info": {
      "item1": "BBC900000000012",
      "item2": "1",
      "item3": null,
      "item4": null
    }
  }
}'
```

## 19. 

```bash
-d '{
  "common": {
    "key_info": {
      "so_id": "9000000000019",
      "so_link_target_id": "TST001"
    },
    "order_info": {
      "service_type_cd": "050",
      "order_type_cd": "002"
    }
  },
  "extension": {
    "add_info": {
      "subscriber_id": "CAF9000000000013",
      "resource_id": "9000000013"
    },
    "detail_info": {
      "item1": "BBC900000000013",
      "item2": "1"
    }
  }
}'
```
