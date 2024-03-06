programa {
funcao inicio() {
// cadeia nameComplete
// inteiro yearBorn
// real hight
// caracter lastLetterName

    // escreva("Informe seu nome completo: ")
    // leia(nameComplete)
    // escreva("Informe seu ano de nascimento: ")
    // leia(yearBorn)
    // escreva("Informe sua altura: ")
    // leia(hight)
    // escreva("Informe a última letra do seu nome: ")
    // leia(lastLetterName)

    // escreva("Seu nome é: ", nameComplete,"\n",
    //         "Seu ano de nascimento é: ", yearBorn,"\n",
    //         "Sua altura é: ", hight,"\n",
    //         "A última letra do seu nome é: ", lastLetterName
    )

}
}

programa {
funcao inicio() {
escreva("QUESTAO 1","\n")
escreva("Olá mundo!","\n")
escreva("Hello world!","\n")
escreva("Hola Mundo!","\n")

    escreva("QUESTAO 2","\n")
    cadeia usuario1, usuario2
    usuario1 = "Pedro"
    usuario2 = "Lhaís"
    escreva("Seja bem-vindo(a): ", usuario1,"\n",
    "Seja bem-vindo(a): ", usuario2,"\n"
    )

    escreva("QUESTAO 3","\n")
    inteiro n1, n2, n3, n4, n5, n6
    n1=38
    n2=10
    n3=-30
    n4=10
    n5=0
    n6=0
    escreva("SOMA = ", n1+n2,"\n",
    "SOMA = ", n3+n4,"\n",
    "SOMA = ", n5+n6,"\n",
    )

}
}

programa {
funcao inicio() {
inteiro vl1, vl2
inteiro prod
escreva("Informe o valor 1: ")
leia(vl1)
escreva("Informe o valor 2: ")
leia(vl2)

    prod = vl1*vl2

    escreva("PROD = ", prod)

}
}

programa {
funcao inicio() {
real nota1, nota2, nota3, nota4, media
escreva("Informe a primeira nota: ")
leia(nota1)
escreva("Informe a segunda nota: ")
leia(nota2)
escreva("Informe a terceira nota: ")
leia(nota3)
escreva("Informe a quarta nota: ")
leia(nota4)

    media = ((nota1+nota2+nota3+nota4)/4)

    escreva("A média desse aluno é: ", media)

}
}

programa {
funcao inicio() {
real n1, n2, a, b, media, nota1Peso, nota2Peso, pesoApesoB
a = 3.5
b = 7.5

    escreva("Informe a primeira nota: ")
    leia(n1)
    escreva("Informe a segunda nota: ")
    leia(n2)

    nota1Peso = n1*a
    nota2Peso = n2*b
    pesoApesoB = a+b

    media = ((n1*a)+(n2*b))/pesoApesoB



    escreva("MÉDIA = ", media)
    escreva("MÉDIA = ", (nota1Peso+nota2Peso)/pesoApesoB)

}
}

programa {
funcao inicio() {
real a, b, c, pesoA, pesoB, pesoC, somaPeso, media, media2
pesoA = 2
pesoB = 3
pesoC = 5

    escreva("Informe a nota A: ")
    leia(a)
    escreva("Informe a nota B: ")
    leia(b)
    escreva("Informe a nota C: ")
    leia(c)

    somaPeso = pesoA + pesoB + pesoC

    media = ((a * pesoA) + (b * pesoB) + (c * pesoC))/somaPeso

    media2 = (((a * pesoA) + (b * pesoB) + (c * pesoC)) / (pesoA + pesoB + pesoC))

    escreva("MÉDIA = ", media,"\n")
    escreva("poupando memória sem salvar o cálculo da lógica na variável\n")
    escreva("MÉDIA = ", media2)

}
}
