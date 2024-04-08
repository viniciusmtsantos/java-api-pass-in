# Pass In API &middot;
> Java Spring Boot
Este projeto consiste na implementação de API para uma "Dashboard de Gestão de Eventos "

- A ferramenta permite que o organizador cadastre um evento e abra uma página pública de inscrição.
- Os participantes inscritos podem emitir uma credencial para check-in no dia do evento.
- O sistema fará um scan da credencial do participante para permitir a entrada no evento.

## Java API
### Funcionalidades da API

#### Para o organizador
- O organizador deve poder cadastrar um novo evento;
- O organizador deve poder visualizar dados de um evento;
- O organizador deve poder visualizar a lista de participantes;

#### Para o participante
- O participante deve poder se inscrever em um evento;
- O participante deve poder visualizar seu crachá de inscrição;
- O participante deve poder realizar check-in no evento;

### Regras de negócio

- O participante só pode se inscrever em um evento uma única vez;
- O participante só pode se inscrever em eventos com vagas disponíveis;
- O participante só pode realizar check-in em um evento uma única vez;
