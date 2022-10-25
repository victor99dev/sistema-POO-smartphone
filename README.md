# 💻 | Projeto: POO - Desafio DIO.

### Projeto integrador feito para por em prática as de C#:

Seja bem vindo ao meu projeto chamado "Criando um Sistema e Abstraindo um Celular com POO", feito totalmente para meus estudos e aperfeiçoamento como profissional. ❤️

- Colocando em prática conceitos obtidos durante a aula.

- Utilizando a linguagem: C#.

### 🎬 | Preview:
Foi inserido o que se pedia nos comentarios TODO.

Um exemplo irei informar aqui foi por o metodo Instalar Aplicativo.


```cs
public Iphone(string numero, string modelo, string imei, int memoria) : base(numero, modelo, imei, memoria)
        {
        }

public override void InstalarAplicativo(string nomeApp)
        {
            Console.WriteLine($"Instalando aplicativo: {nomeApp} via AppStore no Iphone");
        }
```

E aqui informo as propriedades presentes no diagrama mais o construtor.
```cs
 public abstract class Smartphone
    {
        public string Numero { get; set; }
        public string Modelo { get; set; }
        public string IMEI { get; set; }
        public int Memoria { get; set; }

    public Smartphone(string numero, string modelo, string imei, int memoria)
    {
        Numero = numero;
        Modelo = modelo;
        IMEI = imei;
        Memoria = memoria;
    }
```

O código como se pede também é o dispositivo Nokia, afinal ele pede maneiras de diferentes marcas e modelos terem seu próprio comportamento.
```cs
Console.WriteLine("Smartphone iphone:");
Iphone iphone = new Iphone(numero: "1", modelo: "A", imei: "1",memoria: 9);
iphone.Ligar();
iphone.ReceberLigacao();
iphone.InstalarAplicativo("Spotify");

/*-----------------------------------> <-----------------------------------*/

Console.WriteLine("Smartphone Nokia:");
Nokia nokia = new Nokia(numero: "2", modelo: "B", imei: "2",memoria: 15);
nokia.Ligar();
nokia.ReceberLigacao();
nokia.InstalarAplicativo("Deezer");
```
Por fim no Program.cs informo o que se pede e faço um ```dotnet run``` que nos retorna a seguinte resposta:
```
Smartphone iphone:
Ligando...
Recebendo ligação...
Instalando aplicativo: Spotify via AppStore no Iphone
```

<b>Segue a lista de commits para verificar o que foi alterado e incrementado!</b>

<b>[Certificado do Projeto](https://www.dio.me/certificate/FFC7D9C8/share)</b>

## 👩‍💻 Meus Links:

- Github: [Victor Hugo.](https://github.com/torugo99)
- LinkedIn: [Victor Hugo.](https://www.linkedin.com/in/victor-hugo99/)
- Meu Site: [Victor99dev.](http://victor99dev.site/)

### 😀 | Créditos e Agradecimentos:

- Obrigado a DIO a essa oportunidade de UP na minha carreira! ❤️
