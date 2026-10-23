# Guia de Acessibilidade – Adoção Lins

Referências: WCAG 2.1 (nível AA) e eMAG.

## 1. Paleta de cores e contraste

```css
:root {
  --secundaria: #1F2937;
  --fundo: #F0FAF6;
  --primaria: #10B981;
  --texto-claro: #F9FAFB;
  --texto-card: #333333;
  --instagram: #E1306C;
  --card: #FFFFFF;
}
```

Mínimo AA: **4,5:1** para texto normal e **3:1** para ícones e elementos de interface.

| Combinação | Uso | Razão aproximada | Resultado |
|---|---|---|---|
| `texto-claro` sobre `secundaria` | Links do menu no header | 14:1 | ✅ Passa |
| `texto-card` sobre `card` | Textos dos cards e da página de doação | 12,6:1 | ✅ Passa |
| `secundaria` sobre `fundo` | Textos e bordas na página | 13,8:1 | ✅ Passa |
| `secundaria` sobre `primaria` | Texto do botão "Conheça nossos animais" | 5,8:1 | ✅ Passa |
| `instagram` sobre `card` | Ícone do Instagram | 4,3:1 | ✅ Passa (ícone, mínimo 3:1) |
| `card` (branco) sobre `primaria` | Texto branco no botão verde | 2,5:1 | ❌ Reprova — por isso o texto do botão usa `secundaria` |

> Conferir os valores no WebAIM Contrast Checker e anexar os prints.

## 2. Tipografia e hierarquia
- Tamanho base do texto: **16px** (1rem), com `line-height` de 1,5
- Fonte sem serifa e legível, com fallback (`sans-serif`)
- Apenas **um H1 por página**; seções em H2; títulos de cards em H3 (sem pular níveis)
- Textos de apoio nunca abaixo de 14px
- Links distinguíveis do texto comum (cor + sublinhado ou ícone) e botões com área de clique mínima de 44×44px

## 3. Navegação por teclado
- Toda a navegação deve funcionar com `Tab`, `Shift+Tab`, `Enter` e `Espaço`
- Ordem de foco seguindo a ordem visual (header → conteúdo → footer)
- Estado de foco sempre visível (`:focus-visible` com contorno de alto contraste)
- Link "Ir para o conteúdo" no topo da página (skip link)
- Filtros e formulário acessíveis sem mouse

## 4. Imagens e multimídia
- Todas as fotos de animais com `alt` descritivo. Exemplo: `alt="Cachorro caramelo de porte médio sentado na grama"`
- Imagens decorativas com `alt=""`
- Ícones SVG com `aria-label` quando tiverem significado, ou `aria-hidden="true"` quando decorativos
- Vídeos, se houver, com legenda e sem reprodução automática

## 5. Formulários
- Todo campo com `<label>` associado (`for`/`id`)
- Campos obrigatórios indicados no texto e com `required`
- Mensagens de erro em texto, próximas ao campo, sem depender só de cor
- Tipos de entrada adequados (`email`, `tel`)

## 6. Checklist final
- [ ] Contraste verificado nos prints
- [ ] Navegação completa por teclado testada
- [ ] Todas as imagens com `alt`
- [ ] Hierarquia de títulos validada
- [ ] Teste com leitor de tela (NVDA ou VoiceOver) em ao menos uma página
- [ ] Auditoria de acessibilidade do Lighthouse
