# Site da Farmácia 7 de Setembro

Site de apresentação das duas lojas da Farmácia 7 de Setembro, em Cruz - CE.

- **Farmácia 7 de Setembro:** Rua 7 de Setembro, 278, Centro
- **Farmácia 7 de Setembro Popular:** Rua 6 de Abril, 440, Centro

O site inteiro fica em um arquivo só, o `index.html`. Ele não precisa de instalação nem de etapa de compilação: é só abrir o arquivo no navegador.

## Onde alterar cada coisa no `index.html`

- **Endereços, WhatsApp e Instagram:** nos blocos `<article class="loja">`.
- **Horários:** em dois lugares, que precisam ficar iguais:
  - a lista `data-horarios`, que é o texto que aparece na tela;
  - a variável `HORARIOS`, no `<script>` do final, que calcula o aviso "Aberta agora / Fechada".
- **Cores:** nas variáveis de `:root`, no início do `<style>`.
