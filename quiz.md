1. la table contient quatre colonnes dans la base de donnée ( id, description, difficulty, points)

2. Dans la fonctionnalité de l'application décrite par la relation **Quiz** _written by_ **User** sous la forme d'une _user story_ ("en tant qu'utilisateur, j'ai besoin de reponse quizresult afin de remplir ma base de donnée")

3. La relation **Quiz** _written by_ **User** qui a un losange blanc est une relation d'agregation, alors que  la relation **Question** _belongs to_ **Quiz** a un losange noir, signifie que question appartient à quiz donc c'est une relation d'agregation de composition. 

4. Il peut y avoir dans un questionnaire (minimum 1 question et maximum à l'infinit)

5. Chaque question peut avoir (minimum 1 reponse et maximum 4 reponses)

6. Si je supprime une question, je supprime sa reponse parcequ'elle n'a pas de sens d'exister

7. Si je supprime un utilisateur, je supprime son quiz qui n'a pas de sens sans l'utilisateur

8. Pour coder la relation **Tag** _describes_ **Quiz** dans notre base de données. Il faut créer deux tableaux: tag et quiz et definir trois colonnes de chaque

9. La table **Quiz** possede 2 clés etrangeres qui sont user_id (manytoone)

10. Il ya deux relations entre **Answer** et **Question** parceque la description de la reponse doit repondre à la description de la question et vice-versa en même temps une question = une reponse, une à quatre reponses = une question.

11. La classe **QuizResult** se trouve entre les classes **User** et **Quiz** parceque c'est une classe intermediaire qui est une reference de stock du resultat rechercher.

12. Si un utilisateur souhaite tenter à nouveau un questionnaire, est-il prévu qu'il puisse voir à quelles questions il avait bien répondu précédemment? Si oui, où peut-on le voir sur le diagramme? Si non, que faudrait-il rajouter sur le diagramme pour pouvoir l'exprimer



