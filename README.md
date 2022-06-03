# Yaml
YAML Ain't Markup Language (YAML) is a serialization language.

#Some Important Commanly Used Featues :  

#Adding first comments.

--- (#indicates new YAML)

#Starting new YAML here.

name: gourav
surname: jain
middle-name: none
isWorking: yes
weekend-mode: off
hobbies: ~

#Add mutliline String

multiline-string: |
  this is multiline
  String i am
  writing just to
  show you there.

#Add Singleline String 

singleline-string: >
  this is single
  line string which
  will display in
  a single line
  no matter i am 
  writing this in
  a multiline.
  
#Let me create Arrays or Lists for you.
---
items: [1, 2, 3, 4, 5]
names: ["one", "two", "three", "four"]
---
#We can write above syntax as below also (take care of spaces :P)

items:
  - 1
  - 2
  - 3
  - 4
  - 5
names:
  - "one"
  - "two"
  - "three"
  - "four"

#Multiline format of above.
---
items:
  things:
    other-things:
      most-important-things:
        - things1
        - things2
        - things3

#dictionaries
dict: { key:value, key1:value1, key2:value2 }

Useful Sites to validate you YAML doc: 
https://codebeautify.org/yaml-validator
https://www.json2yaml.com/
http://www.yamllint.com/
