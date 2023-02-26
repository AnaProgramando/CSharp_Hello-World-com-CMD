![banner CSharp Hello Word com CMD](https://github.com/AnaProgramando/-CSharp_Hello-Word-com-CMD/blob/5e6c074a466b3202804b63c64dd4a8818dc8620b/banner_CSharp_Hello-Word-com-CMD.png)
----

<img src="https://img.shields.io/static/v1?label=Status&message=complete&color=32CD32&style=for-the-badge"/>

<p align="center">
 <a href="#-welcome">Welcome</a> | 
 <a href="#-d%C3%BAvidas">Dúvidas</a> | 
 <a href="#%EF%B8%8F-contatos">Contatos</a> | 
 <a href="#%EF%B8%8F-autora">Autora</a>
</p>

# 🤗 Welcome

Olá, seja muito bem vinda(o)! 

Tive a ideia de começar o desafio de #100DaysOfCode, além de compartilhar alguns projetos para quem tem interesse em aprender C#, por isso se trata de algo bem simples para quem gostaria de iniciar na programação ou precisa melhorar as suas habilidades.

<br>

## <img align="center" alt="Ana-Csharp" height="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/csharp/csharp-original.svg"> CSharp - Hello Word com CMD

📚 Aproveite o código desse exercício: Como compilar um código com o Prompt? / Como compilar um código com o cmd?

👩‍💻 Refaça do seu jeito

😉 Se tiver qualquer dúvida, me contate

<br>

## 📝 Criando o arquivo

1. Crie uma pasta no seu computador para colocar a aplicação.

2. Crie um novo Documento de Texto e nomeie ele sem espaços no título.

3. Copie o seguinte código no seu arquivo txt:

###### 💬 Obs: Use o bloco de notas para editar o seu arquivo, não precisa de um editor de texto avançado.

```
using System;

class Program
{
	static void Main(string[] args)
	{
		Console.WriteLine("Executando o Projeto 1 - Hello World:");
		
		Console.WriteLine("Olá mundo! Hello world!");
		Console.WriteLine("A execução foi encerrada.");
		Console.WriteLine("Tecle Enter para finalizar...");
		Console.ReadLine();
	}
}
```

<br>

## 📂 Acessando o compilador C#

4. Utilize o Explorador de Arquivos do seu computador para navegar pelos diretórios do Windows até a pasta de Framework do Microsoft.NET.
	- Caminho onde comumente a pasta fica localizada no computador: C:\Windows\Microsoft.NET\Framework
	
5. Abra a pasta da versão 4 que possui os arquivos usados pela CLR (common language runtime).

	> **Visão geral do CLR (Common Language Runtime)** <br>
	> O .NET fornece um ambiente de tempo de execução, chamado de Common Language Runtime, que executa o código e fornece serviços que facilitam o processo de desenvolvimento.<br>
	> Para saber mais sobre CLR, clique [aqui](https://docs.microsoft.com/pt-br/dotnet/standard/clr)!

6. Nesta pasta você encontrará o arquivo csc.exe, copie o caminho desse arquivo
	- Exemplo: c:\Windows\Microsoft.NET\Framework\v4.0.30219\csc.exe 
	<br>
	
	> **csc: C Sharp Compiler** <br>

	> **Opções do compilador de C#** <br>
	> Esta seção descreve as opções interpretadas pelo compilador C#. <br>
	> Para saber mais sobre compilador, clique [aqui](https://docs.microsoft.com/pt-br/dotnet/csharp/language-reference/compiler-options/)

<br>

## 👩‍💻 Compilando o código

7. Aperte a tecla "Windows".

8. Digite "cmd".

9. Abra o Prompt de comando.

10. Digite no Prompt: cd "caminho da pasta onde você salvou a aplicação" e aperte o Enter.
	- Exemplo: cd C:\Users\Fulano\Documents\PastaExercicio	


11. Cole o caminho do csc.exe, dê espaço, cole o nome e a extensão do arquivo da sua aplicação e aperte o Enter. 
	- Exemplo: c:\Windows\Microsoft.NET\Framework\v4.0.30219\csc.exe Exercicio.txt
	
###### 💬 Obs: Para confirmar se deu certo, vá até o diretório da sua aplicação com o Explorador de Arquivos para verificar se apareceu o executável do seu código: "Exercicio.exe".

<br>

## ▶ Execução

12. Para executar com o Prompt digite o nome do arquivo e aperte o Enter.
	- Exemplo: Exercicio.exe
	- Pronto! Agora será possível ver a execução do sua aplicação, pois no Prompt aparecerá a mensagem que você digitou no seu código.
	
```
C:\Users\Fulano\Documents\PastaExercicio>c:\Windows\Microsoft.NET\Framework\v4.0.30219\csc.exe Exercicio.txt
Microsoft (R) Visual C# Compiler version 4.8.4084.0
for C# 5
Copyright (C) Microsoft Corporation. All rights reserved.

This compiler is provided as part of the Microsoft (R) .NET Framework, but only supports language versions up to C# 5, which is no longer the latest version. For compilers that support newer versions of the C# programming language, see http://go.microsoft.com/fwlink/?LinkID=533240


C:\Users\Fulano\Documents\PastaExercicio>Exercicio.exe
Olá, mundo!
```

###### 💬 Obs: Caso você edite esse código, precisará compilar e executar novamente: 
	- c:\Windows\Microsoft.NET\Framework\v4.0.30219\csc.exe Exercicio.txt
	- Exercicio.exe
	
###### ‼ Obs 2: Sempre siga as regras de sintaxe da linguagem - C# é case sensitive, devemos prestar atenção na hora de escrever as palavras-chave / palavras reservadas, pois algumas delas devem começar com maiúsculo, outras com maiúsculo, e todas deve ser escritas de forma exata e correta para as aplicações funcionarem.

<br>

## ❓ Dúvidas

Qualquer dúvida, interaja aqui:
  * Faça perguntas
  * Dê sugestões de melhoria para o projeto
  * Compartilhe suas ideias
  * E interaja sobre o assunto

😉Lembre-se de que esta é uma comunidade que construímos juntos 💪.

<br>

## ✉️ Contatos

Se precisar de ajuda, entre em contato comigo 😉

[<img align="left" alt="Gmail" width="80px" src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white"/>](mailto:anabe.valentim@gmail.com)
[<img align="left" alt="LinkedIn" width="100px" src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/>](https://www.linkedin.com/in/ana-beatriz-valentim)
[<img align="left" alt="Beacons" width="80px" src="https://github.com/AnaProgramando/AnaProgramando/blob/31ac40741768033915a37ec0f949984bf6aad2d1/beacons_logo.png"/>](https://beacons.page/anaprogramando)

<br>
<br>

## 🙋‍♀️ Autora

<div>
  <img align="left" alt="Ana Valentim" width="100px" src="https://avatars.githubusercontent.com/u/31097110?v=4"/>
</div>

<br>
✏️ Feito com ❤️ e C# por <a href="https://github.com/AnaProgramando">Ana Valentim</a>.

💙 Se você gostou desse projeto, dê uma ⭐ e compartilhe!


<br><br>
[⬆ Voltar ao top](https://github.com/AnaProgramando/-CSharp_Hello-Word-com-CMD/blob/main/README.md#) <br>


 <div>
  <img align="center" alt="Pixel-Art" width="1000px" src="https://github.com/AnaProgramando/-CSharp_Hello-Word-com-CMD/blob/1b777174f2391c296e31681b1b42b326168fdb13/x.gif"/>
</div>
