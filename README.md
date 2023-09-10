# 1projetoDIO

Criar uma constante chamada "Steve";

Criar uma variavél opcional chamada "Jobs";

Imprimir a constante e a variavél usando interpolação;

Criar um valor default para a variavél com o nome "Wozniak";

Criar um binding com a opcional, imprimindo os valores da constante e da variavél.

CÓDIGO:

let firstName = "Steve"
var lastName: String? = "Jobs"

print("\(firstName) \(lastName)")

if lastName == nil{
    lastName = "Wozniak"
}


if let opcionalLastName = lastName {
    print("\(firstName) \(opcionalLastName)")
}else{
    print("\(firstName) \(lastName)")
}
