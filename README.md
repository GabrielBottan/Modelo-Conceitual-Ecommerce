# Refinando um Projeto Conceitual de Banco de Dados E-COMMERCE:


Projeto proposto no Bootcamp Suzano - Análise de Dados com Power BI na plataforma DIO.


## Descrição do Desafio:
Modelamos juntos um contexto reduzido de e-commerce. Agora é a sua vez, podes escolher a ferramenta de modelagem para realizar o desafio. Contudo, fique atento! Caso opte por uma variação do modelo entidade relacionamento, como nas ferramentas Mysql Workbench ou DBDesigner será preciso especificar as PK e FKs corretamente. Apesar desse conceito não ser utilizado na modelagem conceitual exploramos brevemente suas definições. Sendo assim, seu empregável será o esquema conceitual para o cenário de E-commerce.


### Objetivo:
Refine o modelo apresentado acrescentando os seguintes pontos:
- Cliente PJ e PF – Uma conta pode ser PJ ou PF, mas não pode ter as duas informações;
- Pagamento – Pode ter cadastrado mais de uma forma de pagamento;
- Entrega – Possui status e código de rastreio;


## Ferramentas utilizadas:
- MySQL Workbench



## Resultado:
![Captura de tela 2024-11-18 174537](https://github.com/user-attachments/assets/97a9d843-09c5-4a4a-b803-4ed9123e246d)

- Para a entidade Cliente foram criadas duas novas entidades PJ_Pessoa Juridica e PF_Pessoa Fisica contendo as informações de CNPJ e CPF.
- No caso de Pagamento a entidade esta atribuída a outras duas entidades afim de detalhar as formas de pagamento : Cartão e Boleto.
- Entrega foi criada para armazenar as informações de envio de cada pedido detalhar como data do pedido, data de envio e data de entrega.



## Certificado:![Captura de tela 2024-11-18 181736](https://github.com/user-attachments/assets/4456fb4d-6686-42d6-9fa3-9e2d59113692)
