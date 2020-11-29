# Padrão Proxy
# Centro Universitário UNIESP
Professora: Drª Alana Morais (alanamm.prof@gmail.com)

Aluno: Evandro do Vale Firmino

# Proxy

 A função do Proxy é "prover um  substituto  ou ponto, através do qual  um objeto possa controlar o acesso de outro." . Ou seja, ele encapsula  um objeto  dentro de outro  objeto que possui a mesma interface de forma que o segundo objeto proxy controla o primeiro objeto que é o objeto real.
 
#   Problema 

Um determinado  sistema precisa acessar um objeto SerSupremo  porém este  objeto não está  disponível (por ser remoto, inaccessível) 

# Solução

Arranjar um intermediário que saiba se comunicar com ele eficientemente. Ou seja, o cliente usa intermediário em vez de sujeito real. O intermediário suporta a mesma interface que o sujeito real. O intermediário contém uma referência para o  sujeito real e repassa chamadas , possivelmente, acrescentando informações ou filtrando  dados  no processo.

# Consequências 

Introduz um nível de intermediação para acessar um objeto. Essas intermediações
adicionais possuem diversos usos tais como: esconder o fato de que um objeto reside em um espaço
de endereçamento diferente, criação de objetos sob demanda e permite que sejam realizadas tarefas
adicionais quando um objeto é acessado.

###link do video https://drive.google.com/file/d/17a16epTCwhlCKij5TXyXeoIMq71vP3Y6/view?usp=sharing
