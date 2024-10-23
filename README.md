# Resumo-do-lab3 
# Configurando Recursos e Dimensionamentos em Máquinas Virtuais na Azure.

# 1. Escolha do Tamanho da VM
   - Ao criar ou redimensionar uma VM, escolha o **tamanho** adequado com base nas suas necessidades de CPU, memória e armazenamento.
     
# 2. Configuração de Recursos
   - CPU e Memória: Determine o número de núcleos de CPU e a quantidade de memória RAM necessária.
   - Armazenamento: Escolha entre discos SSD ou HDD. Configure discos adicionais se necessário (por exemplo, para dados ou backups).
     
# 3. Redimensionamento da VM
   - Você pode redimensionar uma VM existente através do portal:
   - Acesse a página da VM.
   - Clique em "Tamanho".
   - Escolha um novo tamanho e clique em "Redimensionar".
   - Este processo pode causar um breve período de inatividade, então, é recomendável fazer isso durante horários de manutenção.
     
# 4. Configuração de Escalabilidade
   - Para cargas de trabalho variáveis, considere usar Conjuntos de Escala ou Azure VM Scale Sets, que permitem automaticamente aumentar ou diminuir o número de instâncias de VMs com base na demanda.

# 5. Monitoramento e Ajustes
   - Utilize o Azure Monitor para acompanhar o desempenho da VM. Isso permite ajustes na configuração e no dimensionamento conforme necessário.

