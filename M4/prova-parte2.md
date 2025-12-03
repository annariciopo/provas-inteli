# Prova Módulo 4 (2024) - Parte 2 (Prática)

## Instruções

A entrega envolve o envio de um repositório Github contendo sua produção a partir do uso do simulador WOKWI, com montagem de circuito, escrita e compilação de código, além de prints de sua tela.

**É permitido:**

- consultar materiais de referência de código e de componentes IoT, códigos próprios.

**Não é permitido:**

- o uso de celulares e smartwatches (favor DESLIGAR os equipamentos)
- consultar colegas ou interagir com IAs generativas (ChatGPT, Gemini, Bard e afins). 
- copiar e colar respostas prontas, o aluno deve construir suas próprias respostas.

**É recomendado:**

- copiar e salvar frequentemente seu arquivo de código-fonte localmente, para evitar perda de trabalho;

**Ao final desta parte, você deverá:**

- verificar o preenchimento de seu nome, turma e confirmar seu e-mail
- ENVIAR o formulário
- Verificar se recebeu a confirmação de recebimento de ambas as partes da prova por e-mail.

## Avaliação

A avaliação desta segunda parte da prova será feita sobre a montagem correta e funcional do circuito e sobre o código-fonte produzido, além dos prints conforme enunciados abaixo. O avaliador irá subir e executar os arquivos de cada protótipo produzido pelo aluno no simulador WOKWI para avaliação.

Códigos muito semelhantes entre diferentes alunos não serão corrigidos. Apesar da consulta ser permitida, não copie e cole exemplos buscados na Internet, blogs ou IAs generativas, pois um colega pode estar fazendo o mesmo. Faça o seu trabalho, pois você tem capacidade. Os códigos serão comparados sistematicamente, e em caso de comprovação de plágio, os exames serão anulados e as sanções previstas em regulamento interno serão aplicadas.

## Enunciado

Você foi contratado como desenvolvedor de IoT para uma empresa que fabrica semáforos inteligentes para uma pequena cidade. Como parte de seus processos, a empresa desenvolve seus projetos de semáforos em simuladores antes de embarcar o software nos produtos finais. 

O desenvolvedor sênior que estava te mentorando foi para outra empresa às pressas e deixou uma tarefa para você como presente. Eis o projeto que ele estava trabalhando e deixou para você:

[https://wokwi.com/projects/413645635576658945](https://wokwi.com/projects/413645635576658945)

O projeto não está terminado, e sua tarefa será realizar as tarefas abaixo para finalizá-lo. 

Ao final, leia as instruções sobre como fazer seu envio e finalizar a prova.

---

1) Todo o código deve estar padronizado para inglês ou português, incluindo comentários (1,0 ponto);


2) Todas as entradas e saídas devem estar declaradas corretamente na inicialização (1,0 ponto);


3) Todos os leds devem estar apagados na inicialização (até 1,0 ponto);


4) Quando estiver escuro (segundo a leitura analógica do sensor LDR), o protótipo deve ativar o modo noturno e piscar o led amarelo a cada segundo (até 1,0 ponto);


5) Quando estiver claro (segundo a leitura analógica do sensor LDR), o protótipo deve ativar o modo convencional e fazer a temporização alternando entre verde (3 segundos), amarelo (2 segundos) e vermelho (5 segundos) (até 2,0 pontos);


6) Quando estiver claro (segundo a leitura analógica do sensor LDR) e o semáforo estiver no estado fechado (somente led vermelho aceso) e o botão for pressionado, o semáforo deve abrir 1 segundo após o pressionamento do botão (até 2,0 pontos);


7) O protótipo deve suportar debounce na leitura do botão (até 1,0 ponto);


8) Quando estiver claro (segundo a leitura analógica do sensor LDR) e o semáforo estiver no estado fechado (somente led vermelho aceso) e o botão for pressionado 3 vezes, você deve enviar uma requisição HTTP para implementar um alerta (realize uma requisição para o http://www.google.com.br/ para fins de teste) (até 1,0 ponto).

---

Para finalizar, baixe o arquivo .zip do WOKWI (botão "Save > Download project ZIP" conforme imagem abaixo) para sua máquina. Descompacte.
Imagem sem legenda

<br>
<div align="center"> 
    <img src="./assets/wokwidownload.PNG" />
</div>
<br>

Crie um repositório público com seu usuário Inteli no GitHub. Inclua nesse repositório, descompactados:

- seu código 
- o arquivo JSON de conexões 
- o arquivo TXT


Dentro do mesmo repositório, crie um arquivo markdown simples. Nele você deve listar e descrever cada estado do sistema, e incluir as capturas de tela do Wokwi que comprovem o funcionamento correto de cada estado. 

Copie e cole o link para seu repositório Github contendo os arquivos solicitados.

IMPORTANTE: não altere nenhum arquivo após a entrega da prova. Caso seja notada qualquer alteração de arquivo após o horário de entrega deste formulário, sua questão será anulada. Você também é responsável pela manutenção de seu repositório. 