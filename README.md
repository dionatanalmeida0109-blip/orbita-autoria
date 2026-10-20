# Órbita — prova de autoria

**Órbita**, criado por **Dionatan R. de Almeida**. App oficial: https://orbita-opal-beta.vercel.app

Este repositório publica a **chave pública** oficial do Órbita, para que qualquer pessoa possa conferir que a chave dentro do app é a mesma daqui.

- `declaracao-autoria.txt`: o texto assinado, "Órbita, criado por Dionatan R. de Almeida, versão 1.0.0, 20/10/2026".
- `autoria.json`: a declaração, a assinatura ECDSA P-256 / SHA-256 e a chave pública (a mesma de https://orbita-opal-beta.vercel.app/autoria.json).
- `orbita-chave-publica.pem`: a chave pública no formato PEM.
- `*.ots`: provas de data do OpenTimestamps, ancoradas no Bitcoin. Para conferir, rode `ots verify declaracao-autoria.txt.ots`.

Os carimbos foram confirmados no bloco Bitcoin 972335 (minerado em 20/10/2026, 13:57 UTC).

SHA-256 da declaração: `a194474accd714ab65fae8f6f2bd20a87333d1b6d547c1682602504046a5be9a`

A chave privada nunca é publicada.
