﻿# iNFCe
Emissão de NFC-e em Java

Em 2014 comecei o desenvolvimento de um projeto para Emissão de NFc-e em Java.

Minha intenção era escrever um pacote que pudesse ser utilizado tanto em ambiente desktop quanto web.

A principio o projeto era constituido de três .jar:

<ul>
<li><b>iNFCe</b>: o Projeto Principal</li>
<li><b>iQrCode:</b> o gerador de qrCode em .jpg</li>
<li><b>iDanfeNFce:</b> o módulo responsável por ler o XML e gerar o Danfe NFC-e em PDF</b></li>
</ul>

Por incrível que pareça o sistema funcionou :) Na época desenvolvi um PDV (Ponto de Venda) no NetBeans e deu certo: vendia, emitia NFC-e e, por fim, imprimia o Danfe.

Masss... acabei descontinuando o projeto, e desde então nunca mais mexi nele.

O Java se mostrou inadequado para mim, uma vez que meu objetivo era Desktop (sim, muita gente ainda nao gosta de sistemas web), e acabei abandonando o projeto.

Enfim, para o sistema não ficar engavetado por ai, resolvi liberar os fontes para que o pessoal possa dar uma olhada e, quem sabe, ajudar alguém em alguma coisa :)

Ah, que fique bem claro que não sou programador Java (desenvolvo comercialmente em Delphi, ASP.NET C# e PHP), então se você é ninja no Java, nao esquenta se ver muita gambiarra pela frente. Este projeto nao passou disso mesmo... um projeto para aprender um pouco mais sobre Java, WebServices e Certificados Digitais.

Então pessoal, o código está ai. Da forma como se encontra não está funcional (ou seja, não é só chamar na IDE, compilar e pá), esta desatualizado (com o JDK 11 ele já nao conseguia assinar os xml - havia um bug na jdk 11, então utilizava a 7 - não sei se isso foi corrigido), não dou suporte ao projeto (d e s c o n t i n u a d o !), mas o que fora desenvolvido está ai, para quem interessar possa :)


Abraço!
