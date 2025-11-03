# Bot de Criação Automática de Canais de Voz

![Badge](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white)

## Instalação

```bash
npm install
```

## Configurações

```
client.login('Token_do_bot_aqui');         => Token de Autenticação do Bot

const CATEGORY_ID = '';     => ID da categoria onde os canais devem ser criados (substitua pelo seu ID)
let channelCounter = 0;  => // Contador de canais criados
```

## Configurações de slots para as chamadas

```
        const row = new ActionRowBuilder().addComponents(
            new StringSelectMenuBuilder()
                .setCustomId('select_call_size')
                .setPlaceholder('Selecione o número de espaços na call')
                .addOptions([
                    { label: '2', value: '2' }, 
                    { label: '3', value: '3' }, 
                    { label: '4', value: '4' }, 
                    { label: '5', value: '5' },
                    { label: '10', value: '10' },
                    { label: '15', value: '15' },
                    { label: '20', value: '20' },
                    { label: '25', value: '25' },
                    { label: '30', value: '30' },
                ])
        );
```

Feito com ❤️ por Athilio
