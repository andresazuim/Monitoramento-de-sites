# Monitor de Sites em Golang 🌐🔍

## Descrição do Projeto 🚀
O **Monitor de Sites** é uma aplicação desenvolvida em Golang para facilitar a verificação do status de diversos sites de uma forma simples e eficiente. Através de um arquivo de configuração `sites.txt`, o programa realiza verificações periódicas para garantir se os sites estão funcionando corretamente ou se estão retornando erros.

## Funcionalidades 🛠️
1. **Monitoramento Automático:** O programa verifica automaticamente o status dos sites listados no arquivo `sites.txt` em intervalos regulares.
   
2. **Arquivo de Configuração Flexível:** Utilize o arquivo `sites.txt` para configurar os sites que deseja monitorar, permitindo uma fácil personalização.
   
3. **Registro Detalhado em Log:** Todas as verificações são registradas em um arquivo de log (`log.txt`), proporcionando uma visão detalhada do status de cada site ao longo do tempo.

## Como Usar 📋
1. **Clone o Repositório:**
    ```bash
    git clone https://github.com/andresazuim/Monitoramento-de-sites.git
    cd Monitoramento-de-sites
    ```

2. **Configure os Sites:**
    Adicione os URLs dos sites que deseja monitorar no arquivo `sites.txt`, um por linha.

3. **Execute o Programa:**
    ```bash
    go run monitor_de_sites.go
    ```
    Certifique-se de ter o Golang instalado em sua máquina.

4. **Verifique o Log:**
    Os resultados das verificações serão registrados no arquivo `log.txt`. Analise esse arquivo para obter informações detalhadas sobre o status de cada site.

## Requisitos 📦
- Golang 🐹
