# automacao_docs
Sistema Automatizado de Gestão de Documentos

Como funciona
O script roda em loop infinito, verificando a cada 20 segundos se há novas respostas no formulário. Para cada nova entrada, ele:

Lê o Excel sincronizado via OneDrive com as respostas do Forms
Identifica o tipo de atendimento (entrega ou devolução) e seleciona o modelo Word correspondente
Preenche o template .docx com os dados do colaborador (nome, matrícula, serial, hostname, data etc.)
Converte para PDF e salva direto em uma pasta de rede compartilhada
Registra o ID da linha processada para evitar duplicatas em execuções futuras

Resultados:
• 83% de redução no tempo de emissão
• Redução da taxa de erro de 5% para 0%
• Melhoria na padronização e legibilidade dos termos
• Automatização do fluxo operacional de equipamentos
