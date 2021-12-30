# envio-mensagens-whatsapp
 Envio de mensagens pré-programadas para diversos contatos de uma só vez e de maneira autonoma. Funciona a partir de uma interação entre ele e o whatsapp web. Criado totalmente com javascript.
 ## Tecnologias utilizadas
 * ejs e express -> Para criar a parte visual do programa no browser de sua preferencia. 
 * shell -> Por motivos de complicações ele executa comando no terminal para abrir o "backend".
 * puppetter -> Para a automação web.
 * pkg -> Transformar o arquivo principal que geri os outros em executavel.
 * fs , open...
 ## Modo de usar 
 
 1. Quando o programa for executado, imediadamente, abrirá em seu browser uma página. Nela contém um formulario básico para cadastro dos números que se pretende enviar a mensagem , e claro, uma parte para colocar a mensagem. Além de outras opções como colocar o caminho de um arquivo para enviar junto com a mensagem.
 2. Após enviar o formulário o usúario será enviado para outra instacia do browser. Lá o whatsapp web abrirá automaticamente.
 3. Quando o site for iniciado o usúario só precisará ler o qrcode na tela para autenticação. E pronto, agora o programa ira começar a enviar a mensagem para todos contatos cadastrados.
 
 
