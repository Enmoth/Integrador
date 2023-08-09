# Web

# Respositório remoto

#### Descrição de diretório .gits

> Config: Contém as configurações específicas do repositório, como o nome do usuário, endereço de e-mail, etc.

> Description: Esse arquivo é usado pelo servidor Git para fornecer uma descrição do repositório. É geralmente usado em servidores Git públicos.

> Head: É um arquivo especial que aponta para a branch atual em que você está trabalhando. Normalmente, contém o hash (ou referência) da última commit na branch atual.

> Hooks: Este diretório é usado para armazenar scripts de gatilho (hooks) personalizados. Os ganchos permitem que você automatize a execução de scripts antes ou depois de certos eventos no Git, como antes de confirmar ou após receber alterações.

> Index: É onde o Git armazena o chamado "index" ou "staging area", que é uma área temporária onde as alterações são preparadas antes de serem confirmadas.

> Info: Contém informações adicionais sobre o repositório, como os arquivos que estão excluídos e os submódulos utilizados.

> Logs: Armazena logs de referências. É onde o Git registra todas as atualizações que afetam as referências do repositório (branches, tags, etc.).

> Objects: É o diretório onde todos os objetos Git são armazenados. Os objetos são blobs, trees e commits que compõem o histórico e o conteúdo do repositório.

> Packed-refs: Este arquivo contém referências de commits "empacotadas", que são referências de commits que foram compactadas para otimização.

> Refs: Contém todas as referências do repositório, como branches, tags e HEAD. Essas referências apontam para diferentes commits do histórico do repositório.