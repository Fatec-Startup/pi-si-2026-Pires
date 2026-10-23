# Relatório de Redes – Adoção Lins

**URL pública:** _(colar a URL do GitHub Pages)_

## 1. Tráfego de rede (DevTools → Network)
Abrir o site, pressionar `F12`, aba **Network**, recarregar com `Ctrl+Shift+R`.

| Recurso | Status | Tipo | Tamanho | Observação |
|---|---|---|---|---|
| index.html | _ | document | _ | |
| css/style.css | _ | stylesheet | _ | |
| js/main.js | _ | script | _ | |
| _(imagem)_ | _ | image | _ | |

Códigos de status encontrados: _(200, 304, 404...)_ — explicar o que significa cada um e como corrigir eventuais 404.

📸 *Print da aba Network*

## 2. HTTP/HTTPS e DNS
- **HTTP:** protocolo de requisição/resposta entre navegador e servidor, sem criptografia.
- **HTTPS:** HTTP sobre TLS, com criptografia e certificado; o GitHub Pages fornece HTTPS automaticamente.
- **DNS:** traduz o domínio (`usuario.github.io`) para o endereço IP do servidor.
- Resolução do projeto: executar `nslookup usuario.github.io` e colar o resultado.

📸 *Print do cadeado/certificado e do nslookup*

## 3. Auditoria (Lighthouse)

| Métrica | Antes | Depois das otimizações |
|---|---|---|
| Performance | _ | _ |
| Acessibilidade | _ | _ |
| Boas práticas | _ | _ |
| SEO | _ | _ |
| LCP / tamanho total transferido | _ | _ |

Otimizações aplicadas: _(ex.: imagens em WebP, tamanho reduzido, CSS minificado)_

📸 *Print do relatório do Lighthouse*

## 4. Teste de conectividade
| Rede | Dispositivo | Carregou? | Observações |
|---|---|---|---|
| Wi-Fi / cabeada | | | |
| 4G/5G | | | |
