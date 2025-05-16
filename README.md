# sistema-lugares-aula

Sistema interativo para alunos selecionarem seus lugares na sala de aula, com integração ao Google Sheets.

## Funcionalidades

- Mapa visual da sala (6x6 lugares)
- Reserva com confirmação em tempo real
- Área do professor destacada
- Formulário com validação
- Armazenamento local e no Google Sheets
- Totalmente responsivo

## Como Usar

1. **Acesso On-line**:
   ```
   https://vicfera001.github.io/sistema-lugares-aula/
   ```

2. **Configuração**:
   - Edite `index.html` e atualize:
     ```javascript
     const GOOGLE_SCRIPT_URL = "https://script.google.com/macros/s/AKfycbydKKGUvwP1-81e_Mv8dn_qpgXnlmgTR0QBoRqLhGRQn-rcGJ-8Q5YWIb509mrWGEhdVw/exec";
     ```

3. **Para Alunos**:
   - Insira ID e nome
   - Clique no assento desejado
   - Preencha o formulário
   - Confirme a reserva

## Tecnologias

- HTML5 Semântico
- CSS3 Moderno (Grid/Flexbox)
- JavaScript ES6+
- Google Apps Script
- GitHub Pages

## Pré-requisitos

- Conta no Google Drive para o Script
- Planilha Google vinculada
- Navegador atualizado (Chrome/Firefox/Edge)

## Estrutura de Arquivos

```
sistema-lugares-aula/
├── index.html        # Página principal
├── style.css        # Estilos principais
├── README.md        # Este arquivo
└── assets/          # (Opcional) Imagens/icons
```

## Contribuição

1. Faça um fork do projeto
2. Crie uma branch (`git checkout -b feature/nova-funcionalidade`)
3. Commit suas mudanças (`git commit -m 'Adiciona nova funcionalidade'`)
4. Push para a branch (`git push origin feature/nova-funcionalidade`)
5. Abra um Pull Request

## Licença

MIT License - [LICENSE.md](LICENSE.md)

> Desenvolvido por [Victor Ferauche] - [2025]
