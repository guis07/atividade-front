# Registro de prompts e iterações

> Este documento registra o briefing recebido, os prompts de trabalho organizados durante a execução e as decisões aplicadas no código. Não é uma transcrição automática de todas as mensagens internas de ferramenta; é um registro de processo para apresentação do exercício.

## Prompt 1 — briefing inicial
“Crie uma landing page para o restaurante japonês OGURU Sushi & Bar. Use as imagens anexadas como referências visuais do ambiente real. Quero uma página contemporânea, industrial, sofisticada e acolhedora, com tijolos aparentes, estrutura preta, madeira, vegetação e iluminação quente. Evite clichês visuais de restaurante japonês. Inclua hero, apresentação da experiência, destaques de cozinha e bar, galeria do ambiente, chamada para conhecer unidades, navegação e rodapé. Entregue HTML, CSS e JavaScript responsivos.”

## Prompt 2 — identidade visual
“Defina uma identidade visual com pelo menos quatro cores em hexadecimal, descrevendo o papel de cada uma. Priorize carvão, creme, cobre e verde musgo, extraídos das referências. Combine tipografia sans-serif contemporânea com um detalhe editorial discreto. Não use vermelho saturado como cor dominante, fontes pseudo-orientais, sakura decorativa ou fundos com padrões genéricos.”

## Prompt 3 — conteúdo e credibilidade
“Escreva textos curtos, naturais e sensoriais. Evite frases genéricas de IA, exageros como ‘a melhor experiência de todos os tempos’ e informações não verificadas. Os CTAs devem apontar para seções reais ou para o site oficial do OGURU. Não simule um sistema de reserva nem invente preços ou horários.”

## Prompt 4 — movimento e responsividade
“Adicione animações discretas: leve zoom na imagem hero e revelação dos blocos ao entrar na tela. Respeite `prefers-reduced-motion`. Faça o menu virar um menu mobile funcional, garanta leitura em celular e mantenha os botões e links utilizáveis.”

## Prompt 5 — revisão crítica
“Revise o resultado como designer e desenvolvedor: confirme hierarquia visual, contraste, responsividade, coerência da paleta, texto alternativo das imagens e destino dos links. Não deixe elementos interativos sem ação. Diferencie fotos de referência reais das imagens temporárias de comida e documente o que precisa ser substituído antes de publicar.”

## Decisões tomadas
- Usar as imagens do briefing em destaque, em vez de depender de imagens genéricas para representar o ambiente.
- Alternar fundos claros e escuros para criar ritmo de leitura.
- Manter textos concisos, com foco em atmosfera e encontro.
- Usar fotos de comida externas apenas como placeholders e deixar isso documentado.
- Direcionar menu/reservas ao site oficial até que existam URLs específicas confirmadas.
- Implementar menu mobile e animações simples sem framework, para facilitar a leitura e edição do código.

## O que revisar depois de testar
- Conferir no celular se a hero não perde o foco da foto.
- Testar links oficiais e confirmar as páginas atuais de menu/reserva.
- Se disponível, trocar os placeholders de sushi/drink por fotos oficiais licenciadas.
- Validar conteúdo com o restaurante caso a página seja usada fora do exercício acadêmico.
