# Pub/Sub component
**Configuration file structure**

The json configuration file has the following structure:
```json
"pub_subs": {
  "<STORE NAME>": {
    "metadata": {
      "<KEY>": "<VALUE>",
      "<KEY>": "<VALUE>"
    }
  }
}
```
You can configure the key/value configuration items that the component cares about in the metadata. For example, [redis component configuration](https://github.com/mosn/layotto/blob/main/configs/config_apollo_health_mq.json) is as follows:

```json
"pub_subs": {
  "redis": {
    "metadata": {
      "redisHost": "localhost:6380",
      "redisPassword": ""
    }
  }
},
```


**Configuration item description**

Each component has its own special configuration items. Please refer to the documentation for each component.