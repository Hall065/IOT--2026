# Questionário de Eletricidade — Respostas (linguagem simples)

Baseado no Material Didático Integrado (SENAI)

---

## Módulo 1: Composição da Matéria

### 1. Defina matéria e descreva qual é a sua menor parte constitutiva que ainda conserva suas características originais.

**Matéria** é tudo que ocupa lugar no espaço e tem peso (água, ar, madeira, metal, etc.).

A menor parte que ainda guarda as características daquele material é a **molécula**.  
(Se a molécula for quebrada, o material deixa de ser o mesmo.)

---

### 2. O que é a camada de valência de um átomo e por que ela é de extrema importância para a eletricidade?

A **camada de valência** é a camada **mais externa** do átomo, onde ficam os elétrons “de fora”.

Ela é importante para a eletricidade porque é dali que os elétrons podem sair e se mover — e o movimento desses elétrons é o que forma a corrente elétrica.

---

### 3. O que determina se um material é classificado como condutor ou isolante elétrico? Dê 3 exemplos práticos de cada tipo.

O que decide é a **facilidade de os elétrons se moverem** no material:

- **Condutor:** elétrons andam com facilidade → a corrente passa bem.  
  Exemplos: **cobre, alumínio, ferro**.

- **Isolante:** elétrons quase não se movem → a corrente quase não passa.  
  Exemplos: **borracha, plástico, madeira seca**.

---

## Módulo 2: Tensão Elétrica e Eletrostática

### 4. Explique os três processos fundamentais de eletrização: por atrito, por contato e por indução.

1. **Por atrito:** esfregar dois corpos. Um “rouba” elétrons do outro. Ex.: plástico no cabelo.
2. **Por contato:** um corpo já carregado toca outro. Parte da carga passa para o segundo.
3. **Por indução:** um corpo carregado se aproxima de outro **sem tocar**. Ele empurra ou puxa as cargas do outro corpo, deixando-o eletrizado.

---

### 5. Defina Tensão Elétrica (ddp) e indique a unidade oficial e o físico homenageado.

**Tensão elétrica** (ou diferença de potencial) é a “força” que empurra os elétrons para circularem no fio.

- Unidade: **Volt (V)**  
- Físico homenageado: **Alessandro Volta**

---

## Módulo 3: Corrente Elétrica

### 6. Explique a diferença no comportamento dos elétrons livres no condutor antes e após fechar o interruptor.

- **Interruptor aberto (desligado):** os elétrons livres se mexem de forma bagunçada, sem direção. Não há corrente útil.
- **Interruptor fechado (ligado):** a tensão “organiza” o movimento. Os elétrons passam a seguir um caminho — aí surge a corrente elétrica.

---

### 7. O que é corrente elétrica e qual a sua unidade de medida?

**Corrente elétrica** é o fluxo ordenado de elétrons pelo condutor.

- Unidade: **Ampère (A)**

---

## Módulo 4: Resistência Elétrica e Segunda Lei de Ohm

### 8. O que é resistência elétrica? Qual a unidade e o símbolo?

**Resistência elétrica** é a dificuldade que o material oferece à passagem da corrente.

- Unidade: **Ohm**  
- Símbolo da unidade: **Ω**  
- Símbolo da grandeza: **R**

---

### 9. Explique a causa física da resistência em nível atômico e cite o principal efeito térmico.

No átomo, os elétrons que tentam passar **batem** nos átomos do material. Essas batidas atrapalham o fluxo (isso é a resistência) e geram **calor**.

O principal efeito térmico é o **efeito Joule** (o fio/aquecimento esquenta).

---

### 10. Enuncie a Segunda Lei de Ohm. Escreva a equação e descreva cada variável.

A Segunda Lei de Ohm diz que a resistência depende do **material**, do **comprimento** e da **espessura** do condutor.

**Equação:**

\[ R = \rho \cdot \frac{L}{A} \]

- **R** = resistência (Ohm / Ω)  
- **ρ** (rô) = resistividade do material (Ohm·metro)  
- **L** = comprimento do condutor (metro)  
- **A** = área da seção transversal / “espessura” do fio (metro²)

Em resumo: fio **mais longo** → mais resistência; fio **mais grosso** → menos resistência.

---

### 11. Com base na Segunda Lei de Ohm, o que acontece se:

**a) O comprimento for duplicado**  
A resistência **dobra** (fica 2 vezes maior).

**b) A área de seção transversal for triplicada** (fio 3x mais “grosso”)  
A resistência fica **3 vezes menor** (cai para 1/3).

---

## Módulo 5: Multímetro e Protoboard

### 12. O que é um multímetro e quais as três grandezas básicas que ele mede?

O **multímetro** é um aparelho que mede várias coisas elétricas no mesmo equipamento.

As três grandezas básicas:

1. **Tensão** (Volt)  
2. **Corrente** (Ampère)  
3. **Resistência** (Ohm)

---

### 13. Qual o procedimento para medir a tensão em um pino do Arduino?

1. Ligar o multímetro na escala de **tensão contínua (V⎓ / DCV)**.  
2. Colocar a ponta **preta (COM)** no **GND** do Arduino.  
3. Colocar a ponta **vermelha** no **pino** que se quer medir.  
4. Ler o valor no display (ex.: cerca de 5 V ou 3,3 V, conforme o pino/placa).

---

## Módulo 6: Potência Elétrica em Corrente Alternada

### 14. Defina Potência Elétrica e explique sua importância em circuitos CA.

**Potência elétrica** é a quantidade de energia elétrica usada (ou transferida) por segundo — em português simples: **quanto o circuito “consome” ou “entrega” de energia no tempo**.

Em corrente alternada (CA — a da tomada), ela é importante para saber o tamanho certo de equipamentos, fios e quanto se gasta de energia.

---

### 15. Diferencie os três tipos de potência em corrente alternada:

**a) Potência Ativa (P)**  
É a potência que **realmente faz trabalho** (acende lâmpada, gira motor útil, esquenta).  
- Símbolo: **P**  
- Unidade: **Watt (W)**

**b) Potência Reativa (Q)**  
É a potência que **vai e volta** no sistema (fica “circulando” por causa de bobinas e capacitores), sem virar trabalho útil direto.  
- Símbolo: **Q**  
- Unidade: **VAR** (volt-ampère reativo)

**c) Potência Aparente (S)**  
É a potência **total** que parece estar no circuito (combinação da ativa + reativa).  
- Símbolo: **S**  
- Unidade: **VA** (volt-ampère)

---

*Respostas em linguagem simples e objetiva — Hall / SENAI*
