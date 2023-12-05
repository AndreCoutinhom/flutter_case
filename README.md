---

![image](https://github.com/AndreCoutinhom/flutter_case/assets/91290799/6e83c60b-06ac-44da-b994-b32593609386)

---
### Tópicos:
> Desenvolvimento Mobile
>
> Front-end
> 
> Flutter
>
> Programação
---
Desejamos boas-vindas para você que vai mergulhar em mais um case com a gente!

Pegue um café, respire fundo e vamos lá:

Uma dúvida frequente em equipes de desenvolvimento de pequenas e até mesmo grandes empresas é: devo ou não migrar para uma tecnologia diferente?

Este questionamento acontece pois a todo instante surgem novas tecnologias no mercado, novas práticas de usar tecnologias já existentes e diferentes necessidades dos usuários.

A tomada de decisão para mudar ou manter o que já é utilizado deve considerar diversos fatores como: riscos, conhecimento da equipe, experiência do usuário, vantagens para a empresa e muito mais.

Neste case, Augusto Souza, software engineer manager da Quinto Andar, startup focada em vendas e locação de imóveis, explica como a empresa adotou o **Flutter** como principal *stack* de desenvolvimento mobile.

Augusto nos conta sobre todo o processo de adoção desta tecnologia, desde o que fez a empresa tomar a decisão de migrar, passando pela fase de implementação, até chegar nos resultados atuais.

---

* A experiência do Quinto Andar é altamente baseada no navegador pelo mobile.
---
* Tínhamos uma confiança muito grande na [Trusted Web Activity](https://developer.chrome.com/docs/android/trusted-web-activity/)
---
* Para **IOS** tínhamos 2 apps Swift nativas
---
* No entanto haviam resultados negativos. Haviam muitas reclamações voltados para *stack*.
---
* No IOS haviam impactos negativos na estrutura dos times.
![image](https://github.com/AndreCoutinhom/flutter_case/assets/91290799/6bdcca34-0d50-4d0f-8f38-71f271214796)
---

### Cross App development: 

![image](https://github.com/AndreCoutinhom/flutter_case/assets/91290799/1dc67f9f-eae1-47c0-a36a-bdc0fcef8da9)

> Uma forma de trabalhar apps que funcionam em diferentes sistemas operacionais.

![image](https://github.com/AndreCoutinhom/flutter_case/assets/91290799/d59eb62f-dede-449d-9a03-4a4bfca8fea1)

---
* Começamos com React Native, mas percebemos que o [**Flutter**](https://flutter.dev/?gclid=Cj0KCQiAyKurBhD5ARIsALamXaF4sS55NoaJxXOtlwe_79FqGn9-x1Q3GfXvNxEf2knzpxes-lt_klQaAq56EALw_wcB&gclsrc=aw.ds) seria melhor para o nosso contexto.
---
* O uso do **Flutter** diminui as reclamações de *stack*.
---
* O sistema de *packages* do **Flutter** permite integrar as mesmas aplicações do **Android** para o **IOS**.
---
* Validamos muito da qualidade de nosso serviço por *web view*.
---
* O uso do Flutter facilitou o processo de manutenção.
---

### Desvantagens:

* Descompatibilidade com muitas APIs.
* Poucas pessoas que conhecem. Difícil contratação.
* Não ideal para *design system* personalizado.
---

### [Release Train](/release_train.pdf)

> O artigo redata sobre *deployment* contínuo para aplicações mobile.

* [**GitHub Actions**](https://docs.github.com/pt/actions) foi muito usado para automatização das releases 

---

* O Quinto Andar tem um programa de treinamento para **Flutter**.

---

* São raras as pessoas que trabalham com **Flutter**.
---
## Materiais para Estudo

* [**CURSO**: FORMAÇÃO FLUTTER](https://www.alura.com.br/formacao-flutter?_gl=1*n9bxeq*_ga*ODM1Nzk2OTUyLjE2OTgzNDc1Mjk.*_ga_1EPWSW3PCS*MTcwMTUxODkzMi40MS4xLjE3MDE1MTg5MzMuMC4wLjA.*_fplc*YWFVZHhVMDdrSmglMkJLelZNU2xyUGlqWHVoNUt4RmtDbXZrcGxlYnVURjBacDIyZzVEd3pKNkF6Wm5YRkxGJTJCJTJGSXRpSTloUzhNd2x3ZEE2TFYzVHlJNTQ1N051aVc0U29HbmdpdUU2Rkw4c0JBWk4lMkJVRzZHdnNaJTJCRlhrJTJCSVRRJTNEJTNE)
* [**ALURA+**: FLUTTER E O DESENVOLVIMENTO MOBILE](https://cursos.alura.com.br/conhecendo-o-flutter-e-uma-visao-do-desenvolvimento-mobile-hoje-c4)
* [**ALURA+**: FLUTTER 2.0](https://cursos.alura.com.br/flutter-2-0-c840)
* [**HIPSTERS.TECH**: FLUTTER](https://www.alura.com.br/podcast/hipsterstech-flutter-hipsters-183-a380?_gl=1*ei07yk*_ga*ODM1Nzk2OTUyLjE2OTgzNDc1Mjk.*_ga_1EPWSW3PCS*MTcwMTUxODkzMi40MS4xLjE3MDE1MTg5MzMuMC4wLjA.*_fplc*YWFVZHhVMDdrSmglMkJLelZNU2xyUGlqWHVoNUt4RmtDbXZrcGxlYnVURjBacDIyZzVEd3pKNkF6Wm5YRkxGJTJCJTJGSXRpSTloUzhNd2x3ZEE2TFYzVHlJNTQ1N051aVc0U29HbmdpdUU2Rkw4c0JBWk4lMkJVRzZHdnNaJTJCRlhrJTJCSVRRJTNEJTNE)
