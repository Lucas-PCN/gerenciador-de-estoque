# Projeto Gerenciador de estoque

<p>Projeto entregue durante o curso de desenvolvimento Web ministrado pela <a href="https://www.betrybe.com" targe="_blank" rel="nofollow">Trybe</a>.</p>

<p>Obtive a aprovação no projeto completando 100% dos requisitos obrigatórios e opcionais. Efetivando, assim, a conclusão do Bloco 13 (Containers) referente a Aceleração em Java.</p>

## Descrição
O objetivo do projeto foi finalizar algumas configurações e testes para depois disponibilizá-los.


  1 - Foi escrito o Dockerfile em multi-stage dessa aplicação que foi desenvolvida em Java 11;
  
  2 - No arquivo docker-compose.yml, foi configurado a aplicação para subir na porta 8888 e foi linkada com o mongo db (utilizando a versão mais recente e na porta 27017).

  3 - Na classe dos testes, foi realizado algumas configurações do TestContainers. Foram adicionadas as annotations necessárias para que os testes fossem executados.

  > Caso ocorra algum erro, valide se o contâiner foi inicializado corretamente ou se, por exemplo, já tem alguma outra aplicação na porta que foi configurada.
 Caso tenha, encerre essa aplicação para liberar a porta :)

## Rodando o projeto localmente
  1. Clone o repositório
   
     `git@github.com:Lucas-PCN/gerenciador-de-estoque.git`
    
  2. Entre no diretório do repositório que você acabou de clonar:
  
     `cd gerenciador-de-estoque`

  3. Instale as dependências:
    
     `mvn install`

  4. Ative o docker-compose para iniciar a aplicação:
     ` docker-compose up -d`

## 📌 Para testar o projeto
  1. digite o comando no seu terminal
      
      `mvn test`
      
    Os códigos de cobertura de testes, do arquivo src/test/java/com/trybe/acc/java/gerenciadorDeEstoque/CoverageValidationTest.java,
    foram desenvolvidos pela Trybe.

---

Projeto desenvolvido por Lucas Castanheira, para fins didáticos. 2023
