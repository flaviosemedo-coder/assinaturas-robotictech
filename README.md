# Assinaturas Robotictech

Aplicativo estático para a equipe criar assinaturas de e-mail no padrão da Robotictech. O arquivo `index.html` na raiz reúne o editor, os estilos e as imagens. Pode ser servido diretamente, sem build, dependências de servidor ou banco de dados.

[Abrir a demonstração](https://assinaturas-robotictech.flavio-semedo.chatgpt.site/) · [Baixar o pacote para a TI](./assinaturas-robotictech.zip)

## Publicação

1. Escolha o endereço. Um subdomínio possível é `assinaturas.robotictech.com.br`. Também é possível usar uma pasta do site atual, como `/assinaturas/`.
2. Publique o `index.html` na raiz do subdomínio ou na pasta escolhida. Configure o servidor para servir esse arquivo como página inicial e habilite HTTPS com um certificado válido para o endereço.
3. Para um subdomínio novo, use o tipo e o destino do registro DNS indicados pelo provedor que hospedará o arquivo. O endereço da demonstração serve apenas para avaliação. Preserve os registros MX da empresa. Uma pasta no domínio já existente dispensa novo registro DNS.

## Verificação

Abra o endereço HTTPS, preencha nome, cargo e telefone e selecione uma foto de teste. Clique em **Copiar assinatura**, cole no editor de assinaturas do Outlook e confira em uma nova mensagem de teste. Confira foto, alinhamento e links do telefone, site, Instagram e YouTube. Em **Baixar cópia editável**, salve o HTML e reabra o arquivo para verificar os dados personalizados.

O modelo distribuído começa em branco, sem nome, telefone ou retrato pessoal pré-carregado. O editor processa a foto no navegador. Ao copiar a assinatura ou baixar a versão editável, a imagem passa a integrar essa cópia.

## Atualização e retorno

Antes de substituir uma versão publicada, guarde o `index.html` anterior e registre o commit ou tag correspondente. Para retornar, restaure esse arquivo no mesmo caminho e repita a verificação pelo endereço da equipe.
