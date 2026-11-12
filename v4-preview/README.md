# Connect Escolar V4.0 Professional — prévia

Esta pasta contém uma versão de homologação da V4.0. A versão principal em /index.html não foi substituída.

## Preservação de dados
- A configuração do Firebase Realtime Database e os caminhos utilizados pelo sistema foram mantidos.
- Não há migração automática nem limpeza ao abrir a V4.0.
- O arquivo original v3.9.30 está preservado em BACKUP_ORIGINAL.
- Foi incluído backup e restauração dos sete caminhos de dados usados pelo aplicativo.
- A senha local existente continua como estava; ela não é autenticação segura. É necessário revisar Firebase Authentication e as regras do banco em uma etapa separada.

## Instalação
- manifest.webmanifest: manifesto PWA.
- service-worker.js: cache dos arquivos da interface; respostas do Firebase não são armazenadas.
- icons/: ícones para instalação.
- A interface pode ser carregada offline depois do primeiro acesso, mas para gravar e sincronizar com o Firebase é necessária conexão com a internet.

## Homologação
Teste a página /v4-preview/ antes de promover a V4.0 para a raiz do site. Faça e guarde um backup pelo próprio sistema antes de qualquer operação de restauração.
