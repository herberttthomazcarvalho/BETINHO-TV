# TV PLAY — Android TV (projeto inicial)

Este é um projeto-fonte inicial para Android TV/Google TV com:
- Interface de guia inspirada na referência enviada (menu lateral, categorias, canais e programação).
- Navegação por foco e controle remoto usando componentes Compose.
- Painel administrativo de demonstração para cadastrar canais e programas.
- Campo para URL de transmissão autorizada (a reprodução ainda precisa ser ligada ao player).

## Importante
Este pacote é o **código-fonte inicial**, não um APK pronto. Não foi compilado nem testado em um dispositivo neste ambiente.
A senha administrativa atual é apenas de demonstração e vive na memória da execução; não use para proteger dados reais.
O cadastro ainda não usa servidor/banco de dados e não persiste ao fechar o app. Para produção, implementar autenticação no servidor, API e banco de dados.
As categorias e canais mostrados são exemplos; não incluem acesso a canais pagos ou transmissões reais.

## Como abrir e compilar
1. Instale o Android Studio e o JDK compatível.
2. Abra a pasta `TV_PLAY_Android_TV` no Android Studio.
3. Aguarde a sincronização do Gradle e instale os componentes SDK sugeridos.
4. Conecte uma Android TV/Google TV com depuração habilitada ou crie um emulador Android TV.
5. Execute a configuração `app`. Para gerar APK de teste, use **Build > Build APK(s)**.

Para ser publicado na Google Play, revise os requisitos oficiais para apps de TV e teste em dispositivos reais.
