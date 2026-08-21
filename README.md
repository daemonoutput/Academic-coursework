# Academic-coursework
Eis tudo o que aprendi em minha formação Técnica e Universitária na área da Tecnologia da Informação e Comunicação (TIC).


## Matérias
### 1. ORGANIZAÇÃO DE COMPUTADORES E SISTEMAS OPERACIONAIS
A. Arquitetura de Computadores:
|—————————|               |---------|
| CPU     |______BUS______| Memória |
|_________|       |       |_________|
                  |
                  |
                  |
                  |
              |---------|
              | I/O     |
              |_________|

Componentes
CPU
- Unidade de Controle 
- Unidade de Processamento
N é igual a:
-- MMU
↓
-- UDED
↓
-- ULA
↓
-- FPU

(Fabricantes podem adicionar mais outras UP's, no entanto estás são às fundamentais.)

1 Núcleo = 1xN
2 Núcleos = 2xN
3 Núcleos = 3xN
4 Núcleos = 4xN

- REGISTRADORES
-- Propósito Geral
-- Endereçamento
-- Controle
-- Configuração

MEMÓRIA RAM
- Principal (DRAM)
- Cache (SRAM)
-- L1 (
-- L2 (
-- L3 (

BUS = BARRAMENTOS
- Endereços
- Controle
- Dados (Dados e outro endereço)

I/O ou E/S = Input and Output ou Entrada e Saída.

Uma Unidade de Processamento Central (CPU) de computador ou simplesmente processador é composto por muitos circuitos eletrônicos que podem estar **desligados** ou **ligados**. Esses dois estados são representados no formato de código binário sendo 0 ou 1, que são chamados de dígitos binários cujo bits representam um conjunto de dígitos binários.

Tenha em mente que:
1 bit = 0 ou 1.
1 nibble = 4 bits = 4 dígitos binários.
1 byte(B) = 8 bits = 8 dígitos binários.
1 KeraByte(KB) = 1024¹ B = 8192 dígitos binários.
1 MegaByte(MB) = 1024² B = 1.048.576 KB = 8388.608 dígitos binários.
1 GigaByte(GB) = 1024³ B = 1073.741.824 MB = 8589.934.592 dígitos binários.
1 TeraByte(TB) = 1024⁴ B = 1099.511.627.776 GB = 8796.093.022.208 dígitos binários.
1 PetaByte(PB) = 1024⁵ B = 1125.899.906.842.624 TB = 9007.199.254.740.992 dígitos binários.
1 ExaByte(EB) = 1024⁶ B = 1152.921.504.606.846 e 976 EB = 9223.372.036.854.775.808 dígitos binários.
1 ZettaByte(ZB) = 1024⁷ B = 1180.591.620.717.411.303.424 ZB = 
1 YottaByte(YB) = 1024⁸ B = 1208.925.819.614.629.174.706.176 YB =

Além disso pode ser composto de diversos parâmetros tais como: tamanho da palavra, compatibilidade binária, capacidade de endereçamento e clock.
**Tamanho da Palavra:** É a quantidade mínima de bits para representar a instrução mais simples do processador. O tamanho da palavra também determina quantos bits a unidade decodificadora de instruções utiliza a cada ciclo de decodificação.
**Compatibilidade Binária:** 
**Capacidade de Endereço:** É a quantidade máxima de endereços diferentes que um processador pode gerar. Endereços estes que na sua maioria são para acessar a memória. Devemos observar que a capacidade de endereçamento não possuí nenhuma relação com o tamanho da palavra e na maioria das arquiteturas cada endereço de memória armazena 1 byte de informação.
**Clock:**

Um processador pode de:
2x4 = 8 bits (2³) = 2⁸ = 256 combinações de bytes de endereços.
2x8 = 16 bits (2⁴) = 2¹⁶ = 65536 combinações de bytes de endereços.
2x16 = 32 bits (2⁵) = 2³² = 4294967296 combinações de bytes de endereços.
2x32 = 64 bits (2⁶) = 2⁶⁴ = 18446744073709551616 combinações de bytes de endereços.

Isto é: 
Assembly → Assembler → C
[OP-Code|Endereços]
ADD End¹, End²; End¹ ← End¹ + End²

Ex.: 8 bits
OP-Code            End1               End2
[][][][][][][][] + [][][][][][][][] + [][][][][][][][]

256 B
65536 bytes ÷ 1024 = 64 KB 
4294967296 bytes ÷ 1024 = 4194304 KB ÷ 1024 = 4096 MB ÷ 1024 = 4GB
18446744073709551616 ÷ 1024 = 18014398509481984 KB ÷ 1024 = 17592186044416 MB ÷ 1024 = 17179869184 GB ÷ 1024 = 16777216 TB ÷ 1024 = 16384 PB ÷ 1024 = 16 EB



