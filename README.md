# Prometheus e Grafana - IT TALENT - DevOps 2024
Este projeto teve como objetivo criar um dashboard no Grafana utilizando dados coletados pelo Prometheus. A atividade envolve a configuração de uma instância do servidor do Prometheus, a conexão do Grafana a essa instância e a criação de painéis para monitoramento.

## Etapas Grafana
### 1. Conectar Grafana ao Prometheus
- Abra o Grafana e vá para a seção de configurações.
- Adicione uma nova fonte de dados e selecione Prometheus.
- Configure a URL do seu servidor Prometheus e salve a configuração.
  
### 2. Adicionar o Dashboard Padrão
- No Grafana, vá para a seção de dashboards e escolha "Import".
- Importe o dashboard "Prometheus 2.0 Stats".
- Confirme a importação e você verá vários painéis padrão exibidos.
  
### 3. Remover Painéis Padrão
- Selecione cada painel individualmente clicando nele.
- Digite "p" e depois "r" para excluir o painel.
- Repita o processo até que todos os painéis tenham sido removidos.
  
### 4. Criar Novos Painéis
- Após excluir todos os painéis, você verá a mensagem de que não há visualizações. Clique em "Add Visualization".
- Escolha Prometheus como fonte de dados.
- Será aberta uma janela para a criação de um novo painel. Na parte inferior, selecione uma métrica qualquer para iniciar.
  
## Conclusão
Com as etapas acima, foi configurado um dashboard personalizado no Grafana utilizando dados do Prometheus. Este exercício ajudou a entender como criar e manipular painéis no Grafana, bem como a importância de monitorar métricas específicas para a gestão eficiente de sistemas.

## Dashboard
![Imagem1](https://github.com/ingridmoitinho/prometheus-grafana/blob/main/Print%20Prometheus%20e%20Grafana.png)

