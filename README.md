# xehash

xehash is a variant of [Cryptonight-GPU](https://ryo-currency.com/cn-gpu/) algorithm (forked from [fphash](https://github.com/CyberChainXyz/fphash-go)), with parameters below:

```
MEMORY = 64 * 1024
ITER = 0x500
```

## Usage

To use these bindings in your Go project, import the package:

```go
import "github.com/XeChain/xehash-go"

intput := []uint8{1, 2, 3, 4, 5}
result := xehash.Hash(input) // [32]uint8
```
