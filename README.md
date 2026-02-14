========================================================
PROJECT NOVA 2026 — OTIMIZADOR
========================================================
Versão: [1.0]
Autor/Créditos: @naos0uele
Marca/Projeto: Irontune

--------------------------------------------------------
0) O QUE É (E O QUE NÃO É)
--------------------------------------------------------
O Project NOVA é um otimizador para Windows feito em PowerShell, com foco em:
- limpeza de arquivos inúteis,
- ajustes de energia/desempenho,
- redução de processos e tarefas desnecessárias,
- correções comuns de lentidão,
- e um modo “game booster” para reduzir interferências em segundo plano.

O que ele NÃO é:
- “RAM booster milagroso” (isso não existe).
- “turbo mágico” que dobra FPS em qualquer PC.
Ele melhora o cenário real: menos lixo, menos gargalo bobo, energia correta, processos chatos controlados.

Meu ponto de vista: otimização de verdade é mais “higiene + bons ajustes” do que truque. O NOVA é pra isso.

--------------------------------------------------------
1) REQUISITOS
--------------------------------------------------------
- Windows 10 ou Windows 11
- PowerShell 5.1 (padrão do Windows) ou PowerShell 7+
- Recomendado: executar como Administrador (para aplicar tudo)
- Espaço em disco: mínimo 200 MB livres (para operações de limpeza e logs)

--------------------------------------------------------
2) COMO EXECUTAR (PASSO A PASSO)
--------------------------------------------------------
1) Extraia o .ZIP (não execute de dentro do .zip)
   Clique com o botão direito no arquivo → “Extrair tudo”.

2) Abra a pasta extraída.

3) Execute como Administrador:
   Clique com o botão direito no arquivo .ps1 → “Executar com PowerShell”
   OU abra o PowerShell como Administrador e rode:

   - Método recomendado (sem mudar nada permanente no Windows):
     powershell -NoProfile -ExecutionPolicy Bypass -File ".\ProjectNova.ps1"

Observação:
- O arquivo precisa ter extensão .ps1. Se estiver como “ProjectNova” sem extensão, renomeie para “ProjectNova.ps1”.

--------------------------------------------------------
3) MODOS / OPÇÕES (O QUE O SCRIPT NORMALMENTE OFERECE)
--------------------------------------------------------
Dependendo da versão do Project NOVA, o menu pode incluir módulos como:

A) Otimização segura (recomendada)
- Ajusta configurações de energia para reduzir “capamento” de performance
- Reduz tarefas e serviços não essenciais (sem mexer no que quebra o Windows)
- Ajusta configurações comuns que geram lentidão e travadinhas
- Faz rotinas de limpeza (TEMP, caches, resíduos comuns)

B) Limpeza e manutenção
- Limpeza de temporários do Windows e do usuário
- Limpeza de logs e sobras comuns (com cuidado)
- Organização geral para reduzir “entulho”

C) Disco e armazenamento (HD e SSD)
- Para SSD: otimizações compatíveis + TRIM (quando suportado)
- Para HD: rotinas de manutenção/otimização que não detonam o disco
- Correções comuns de “100% do disco” (quando aplicável)
Obs: “100% do disco” pode ter várias causas (serviços, indexação, driver, update, malware, disco morrendo).
O NOVA tenta as correções mais seguras primeiro.

D) Game Booster (opcional)
- Reduz processos em segundo plano
- Prioriza o jogo (dependendo da versão)
- Ajusta energia para manter desempenho estável durante a sessão
Obs: Game Booster é para “limpar interferência”, não para criar potência do nada.

E) Diagnóstico rápido (quando existe)
- Mostra pontos comuns que ferram performance (inicialização pesada, disco cheio, etc.)
- Indica ações recomendadas

F) Reversão / Restaurar (quando existe)
- Retorna ajustes para o padrão
- Ou orienta usar ponto de restauração

--------------------------------------------------------
4) SEGURANÇA E REVERSIBILIDADE
--------------------------------------------------------
O Project NOVA é pensado para ser:
- seguro,
- reversível,
- e com log do que foi feito.

Boas práticas (recomendadas):
- Feche programas importantes antes de rodar
- Use a opção de criar Ponto de Restauração (se o script oferecer)
- Rode o modo “seguro” primeiro, antes de opções agressivas

Importante:
- Nenhum otimizador é “100% universal” porque cada PC é um ecossistema diferente.
- Se algo ficar estranho após ajustes, use o módulo de reversão (se houver) ou restaure pelo Windows.

--------------------------------------------------------
5) LOGS / RELATÓRIOS (MUITO IMPORTANTE)
--------------------------------------------------------
O Project NOVA geralmente gera logs/transcript para ajudar em:
- auditoria do que foi alterado,
- diagnóstico se algo falhar,
- e prova do que foi aplicado.

Os logs normalmente ficam em:
- Pasta TEMP do Windows (ex: %TEMP% ou %LOCALAPPDATA%)
- Ou dentro de uma pasta do próprio ProjectNova (depende da versão)

Se o script “fecha sozinho”, 90% das vezes o log diz o motivo.

--------------------------------------------------------
6) PROBLEMAS COMUNS (E COMO RESOLVER)
--------------------------------------------------------
A) “Não abre / fecha sozinho”
- Abra um PowerShell como Administrador
- Execute pelo terminal (assim você vê o erro na tela):
  powershell -NoProfile -ExecutionPolicy Bypass -File ".\ProjectNova.ps1"
- Verifique o log/transcript gerado

B) “ExecutionPolicy bloqueou”
Use o comando com Bypass (não muda nada permanente):
  powershell -ExecutionPolicy Bypass -NoProfile -File ".\ProjectNova.ps1"

C) Antivirus/SmartScreen reclamando
Scripts e otimizadores podem dar “falso positivo” por mexerem em configurações.
Baixe sempre da fonte oficial do autor e confira o arquivo.

D) “100% do disco continua”
Pode ser:
- driver SATA/NVMe,
- Windows Update travado,
- indexação,
- serviço específico,
- disco com saúde ruim.
O NOVA ajuda nos casos comuns, mas não faz milagre em hardware com problema.

--------------------------------------------------------
7) BOAS PRÁTICAS (RESULTADO MELHOR)
--------------------------------------------------------
Para sentir diferença real:
- mantenha pelo menos 15% do disco livre
- desinstale programas que você não usa
- evite 30 apps iniciando junto com o Windows
- atualize drivers (principalmente chipset/storage/vídeo)
- SSD faz muita diferença (quando possível)

Meu ponto de vista: o “PC voando” é mais “menos bagunça + ajustes certos + disco saudável”
do que qualquer botão mágico. O NOVA é um bom “faxineiro técnico” do sistema.

--------------------------------------------------------
8) LICENÇA / USO
--------------------------------------------------------
- Uso por sua conta e risco (normal para ferramentas de sistema).
- Você é responsável por aplicar e entender as opções escolhidas.
- Recomendo usar o modo seguro e criar ponto de restauração.

--------------------------------------------------------
9) CONTATO / SUPORTE
--------------------------------------------------------
TikTok/Créditos: @naos0uele

========================================================
FIM DO LEIA-ME
========================================================
