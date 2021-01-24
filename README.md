# Valve Keyvalues File Suppport

Add the Valve Keyvalues file suppport to VSCode

Supports:
```
.vmt
.qc
.kv
.txt
.res
.vmf
.vmx
.vdf
.fgd
.vpc
.acf
```

## Features

### VMT keyvalues autocomplete.

### VMT Template

Use ```>``` to trigger template, for example: 
```
>lmg
```
this will trigger the LightmappedGeneric Shader VMT Template, then press the Tab, it should insert the template to your code.

Template List:
```
WorldVertexTransition -> wvt
LightmappedGeneric -> lmg
UnlitGeneric -> ug
Proxies -> pro
AnimatedTexture -> at
```

I think this is useful for me🤔.

# Release Notes
## 0.0.6
Add vpc and fgd to support list
## 0.0.4
Add support for keyvalue without the quote mark
Add .qc back to support list
### 0.0.5
bug fix for 0.0.4

## 0.0.3
Remove .txt .qc from support list

## 0.0.2

Added FGD support (thanks @Gocnak)

## 0.0.1

Initial release of this.