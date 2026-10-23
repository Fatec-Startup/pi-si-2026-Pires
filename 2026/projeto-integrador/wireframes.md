# Wireframes – Adoção Lins

## Links
- **Figma:** https://www.figma.com/design/c1eJU1BHgjMGCrA4goyZNI/Projeto-Integrador?node-id=0-1&p=f&t=KZDZSa02LXHiANo1-0
- **Imagem dos wireframes:** `assets/Wireframes_do_Site_Amor_de_Patas.png`

![Wireframes do site Adoção Lins](assets/Wireframes_do_Site_Amor_de_Patas.png)

## Telas

### 1. Página Inicial (Home)
- Hero com mensagem principal ("Dê uma nova chance de vida!") e botão de chamada para ação
- Faixa com 3 valores da ONG: Resgate e cuidado, Adoção responsável, Mais famílias felizes
- Seção "Animais em destaque" com 4 cards (foto, nome, espécie, idade e botão "Quero adotar") e link "Ver todos"
- Bloco informativo "Adotar é um ato de amor!" com botão "Saiba mais"
- Rodapé com links e redes sociais

### 2. Animais para Adoção
- Cabeçalho da página com título e texto de apoio
- Barra de filtros: busca por nome, tipo, idade e porte
- Grade de cards (foto, nome, espécie • idade • porte, botão "Quero adotar")
- Bloco "Adote com responsabilidade"

### 3. Sobre / Contato
- Missão da ONG com ilustração
- Números de impacto (+500 animais resgatados, +300 adoções, +50 voluntários)
- Dados de contato (endereço, telefone, e-mail, redes sociais)
- Formulário: Nome, E-mail, Mensagem e botão Enviar

## Arquitetura de informação (mapa do site)

```
Adoção Lins
├── Início
│   ├── Hero + chamada para ação
│   ├── Valores da ONG
│   ├── Animais em destaque
│   └── Adoção responsável
├── Animais
│   ├── Filtros (busca, tipo, idade, porte)
│   └── Cards de animais
├── Sobre
│   ├── Missão e números
│   └── Equipe/voluntários
└── Contato
    ├── Dados de contato
    └── Formulário
```

## Hierarquia visual
1. **Título principal** (H1) e botão de ação em destaque
2. **Fotos dos animais** como elemento de maior atração visual
3. **Botão "Quero adotar"** com cor de destaque em todos os cards
4. Informações secundárias (idade, porte, textos de apoio) em tamanho menor
5. Header e footer em cor escura para delimitar a estrutura da página

## Heurísticas de Nielsen

| Heurística | Como o projeto atende |
|---|---|
| Visibilidade do status do sistema | Item ativo destacado no menu; mensagem de confirmação após enviar o formulário |
| Correspondência com o mundo real | Linguagem simples ("Quero adotar", "Conheça nossos animais") |
| Controle e liberdade do usuário | Menu sempre visível e link "Ver todos" para voltar à listagem |
| Consistência e padrões | Mesmo header, footer e estilo de card em todas as páginas |
| Prevenção de erros | Campos obrigatórios marcados com * e tipos de entrada adequados (email, tel) |
| Reconhecimento em vez de memorização | Ícones junto aos textos; filtros com rótulos claros |
| Flexibilidade e eficiência | Filtros e busca por nome agilizam quem já sabe o que procura |
| Design estético e minimalista | Poucos elementos por seção, bastante espaço em branco |
| Ajuda a reconhecer e corrigir erros | Mensagens de erro específicas abaixo de cada campo |
| Ajuda e documentação | Seção "Adote com responsabilidade" e "Saiba mais" |
