# binario_llama_cpp_kaggle

Binario pre-compilado do llama.cpp para Kaggle com NVIDIA Tesla T4.

## Build validado

- Linux x86_64
- NVIDIA Tesla T4
- 2 GPUs testadas
- CUDA habilitado
- Compute Capability 7.5
- VMM habilitado
- llama.cpp commit: `9d77fa17254e1dee4b9e92504c91611a60b1359f`
- Release tag: `kaggle-t4-9d77fa17`

## Download

```text
https://github.com/guaxi-123/binario_llama_cpp_kaggle/releases/download/kaggle-t4-9d77fa17/llama-server-kaggle-t4.tar.gz
```

## SHA256

```text
dbd3f1ed1d76b7cebdb382194a6ad76d0fd69753df1845e1f4a179fb29af3241
```

## Download no Kaggle

```bash
wget -O llama-server-kaggle-t4.tar.gz \
  "https://github.com/guaxi-123/binario_llama_cpp_kaggle/releases/download/kaggle-t4-9d77fa17/llama-server-kaggle-t4.tar.gz"
```

## Validar SHA256

```bash
echo "dbd3f1ed1d76b7cebdb382194a6ad76d0fd69753df1845e1f4a179fb29af3241  llama-server-kaggle-t4.tar.gz" | sha256sum -c -
```

## Extrair

```bash
tar -xzf llama-server-kaggle-t4.tar.gz
```

## Testar

```bash
./llama-server-kaggle-t4/llama-server --version
./llama-server-kaggle-t4/llama-server --list-devices
```

Resultado esperado:

```text
Available devices:
  CUDA0: Tesla T4
  CUDA1: Tesla T4
```
