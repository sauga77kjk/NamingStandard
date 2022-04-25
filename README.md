# Unified Naming Convention
aka UNC, is an organization between executor developers to provide a unified scripting api for our scripters.

**Please go to our official website for better styled information: https://scriptunc.org/**

## Why?
Over the years scripting has gotten more and more complex to support multiple executors. This is because of the many unique naming conventions various executors use.

Consider the following scenario. You want to know if a function belongs to the executor or not. In order for this code to be cross compatiable with all executors code like this is needed:
```lua
local is_executor_closure = is_syn_closure or is_fluxus_closure or is_sentinel_closure or is_krnl_closure or is_proto_closure or is_calamari_closure or is_electron_closure or is_elysian_closure
```
This is reality for scripters who want cross compatibilty in their scripts. Scripters shouldn't have to do such laborous work just to attain cross compatability. The UNC seeks to solve this problem using naming conventions everyone agrees upon and follows.

One variant of a script should naturally work on all script executors which have their environment properly fitted to the UNC. 

## How?
The UNC provides standards for naming conventions as well as api functionality. The standards written in  markdown on this github. Edits or additions are done through pull requests. Edits and additions are manually approved by the UNC council and discussed by everyone.

## Supporting UNC
As a product owner, your support of UNC by following the api will result in a far smoother experiencer for scripters, as they are able to work on scripts that they can confidently say will work on **most** products. Once you have integrated UNC's api, you can display so by adding the badge to your website, thread or application.

You can find the badge here: https://scriptunc.org/badge

This will notify people of your alliance in providing scripters with an easier method of engineering scripts that your consumers can enjoy.

## Contributing
Go [here](CONTRIBUTING.md) for a guide on contributing.
