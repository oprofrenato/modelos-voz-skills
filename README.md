# Modelos de voz para transcrição

Cópia dos modelos de transcrição de fala **Whisper** (OpenAI), no formato
**faster-whisper** (SYSTRAN), usados pelas skills de edição de vídeo.

Os arquivos são idênticos aos originais publicados em
`Systran/faster-whisper-small` e `Systran/faster-whisper-base`. O arquivo
`model.bin` de cada modelo foi dividido em partes menores; o `manifesto.json`
traz o SHA-256 de cada parte e do arquivo completo, para conferência depois de
juntar as partes.

| Pasta | Modelo | Tamanho |
|---|---|---|
| `small/` | Whisper small | ~480 MB |
| `base/` | Whisper base | ~145 MB |

Esses modelos só transcrevem: transformam fala em texto. Não geram nem imitam voz,
não aprendem com o uso e rodam inteiramente no computador de quem usa.

## Licença

MIT. Veja `LICENSE` (OpenAI pelos modelos Whisper; SYSTRAN pela conversão).
