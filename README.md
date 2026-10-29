# FovSensi Setup

Instalador oficial da plataforma **FovSensi** — https://fovsensi.com.br

## Download

A última versão do instalador fica em
[**Releases**](https://github.com/FOVSENSI/fovsensi-installer/releases/latest).

Baixe o `FovSensi-Setup.exe` da release mais recente e execute. O instalador
faz download e instalação da versão atual do app em
`%LOCALAPPDATA%\FovSensi\bin\`.

## Como funciona

1. O setup consulta a API da FovSensi para obter o manifesto da versão atual.
2. Verifica assinatura Ed25519 do manifesto contra chave pública embutida no
   próprio instalador.
3. Baixa o binário do app em HTTPS.
4. Verifica SHA-256 e tamanho declarados no manifesto.
5. Instala em `%LOCALAPPDATA%\FovSensi\bin\LDR.exe`.
6. Executa o app e encerra.

## Suporte

- Site: https://fovsensi.com.br
- Conta: https://fovsensi.com.br/conta
- Suporte: suport@fovsensi.com

## Licença

Software proprietário. (c) 2026 FovSensi.
