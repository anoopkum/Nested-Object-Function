import json

sampleJson = """{
   "class":{
      "student":{
         "name":"jhon",
         "marks":{
            "physics":70,
            "mathematics":80
         }
      }
   }
}"""

import json
sampleJson = """{"a":{"b":{"c":"d"}}}"""

sampleDict = json.loads(sampleJson)
if 'd' in sampleDict['a']['b']['c']:
    print(sampleDict['a']['b']['c'])


def nested_object(input_object, find_key):
    internal_value = input_object
    for k in find_key:
        internal_value = internal_value.get(k, None)
        if internal_value is None:
            return None
    return internal_value

print(nested_object({"a":{"b":{"c":"d"}}},["a","b","c"])) #1
print(nested_get({"a":{"bar":{"c":1}}},["a","b","c"])) #None
