# Points

- Topic modeling ou modelagem por tópicos permite analisar grandes volumes de dados (textos) agrupando documentos por tópicos

- A maioria dos dados textuais são sem rotulos (unlabeled) fazendo com que não seja possível a análise supervisionada (aprendizado supervisionado) para a criação de modelos de ML

- Normalmente os documentos que são agrupados juntos se assemelham no tópico da ideia, cabe ao usuário programador entender aquilo que está por trás

- Um tipo de agrupamento por tópicos é o LDA (Latent Dirichlet Allocation), que é um modelo estatístico que tenta juntar palavras com o mesmo sentido/ideia
    - Um documento vai ter sua classificação por meio de um tópico e dentro de cada tópico, que será composto por palavras, terá sua classificação e agrupamento

- Dessa forma, o npr.Topic quer dizer que cada row tem um certo topico e o conteudo dessa row em cada um deles se assemelha a certo tópico, que anteriormente foi separado em 7. Dessas, o algoritmo vai dizer para cada row qual é o mais parecido com ele e a partir disso vai dizer qual tópico será. Para certificar isso, basta olhar o tópico e ir no loop para checar quais são as palavras que provavelmente vão se assemelhar com a ideia da row que está sendo analisada