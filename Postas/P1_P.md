# Logicalis - Hackathon 2022

[Home](../README_P.md) - [Next](P2_P.md)

<p align="center">
  <img src="infraTW.png" alt="Infraestructura Hackathon"/>
</p>

[Leia em espanhol](P1_P.md)

# Posta 1 - Habilitar SSH
## Meta
Neste post devemos escrever um código em python para Habilitar SSH pela API REST, atendendo aos seguintes requisitos:

* Salve o log de execução no modo "depuração".
* Validar (via REST API) a cada 45 segundos que a conexão SSH está habilitada. ***(Não é possível usar time.sleep)***
* Solução se o acesso SSH estiver desabilitado ou se o TELNET estiver habilitado



> O arquivo de log deve ser gerado em 'output/log/HT22.log' dentro de 'HT22'
>
> Para gerar a pasta de log utilizamos o seguinte comando:
> ~~~bash
> mkdir $HOME/output/log
> ~~~


> POSSÍVEIS CASOS ESTADOS:
>
> *Se **SSH** estiver desabilitado, ele deve ser **habilitado***
> 
> *Se **TELNET** estiver ativado, deve ser **desativado***


> Metodos HTTP:
> - GET
> - PUT


> Credenciais:
> ~~~bash
> admin:hackathon
> ~~~


> Headers:
>  ~~~bash
> Content-type: application/yang-data+json 
> Accept: application/yang-data+json
> ~~~


> Solicitar endereço: 
> -  https://10.54.109.X:443/restconf/data/Cisco-IOS-XE-native:native/line/vty
> 
> X: Endereço de cada grupo
> 

## Contexto

Eles são solicitados a manter a conexão SSH de um WLC ativa, reconfigurando (se necessário) o WLC pela API REST a cada 45 segundos, mantendo um registro da execução do código em um arquivo HT22.log.

## Validação

O estado da conexão SSH deve ser ativado continuamente, se necessário, a cada 45 segundos. Solicitar validação com um coach.

[Home](../README_P.md) - [Next](P2_P.md)
