# Aula 11 – Redes de Computadores: Topologias, Dispositivos e Meios

## Identificação

| Campo        | Informação                          |
|--------------|-------------------------------------|
| Disciplina   | Redes de Computadores               |
| Aula         | 11                                  |
| Grupo        | ________________________            |
| Integrantes  | ________________________            |
| Matrículas   | ________________________            |
| Data         | ________________________            |

---

## Descrição do Trabalho

Este repositório contém os entregáveis da **Aula 11**, abordando a organização física e lógica das redes de computadores: topologias de rede, comparação entre dispositivos de interconexão e classificação dos meios de transmissão.

---

## 1. Topologias de Rede

Diagrama com as quatro principais topologias de rede, cada uma em seu próprio painel:

| Topologia | Dispositivo Central | Característica Principal |
|-----------|---------------------|--------------------------|
| **Estrela (Star)** | Switch | Falha de um host não afeta os demais |
| **Barramento (Bus)** | Cabo coaxial compartilhado | Meio único; colisões frequentes; legada |
| **Anel (Ring)** | Token (controle de acesso) | Dados circulam em sentido único; Token Ring/FDDI |
| **Malha (Mesh)** | Roteadores interligados | Alta redundância; tolerante a falhas |

![Topologias de Rede](topologia.png)

---

## 2. Quadro Comparativo de Dispositivos

Comparação entre os três principais dispositivos de interconexão de redes:

| Dispositivo | Camada OSI | Função | Exemplo Real |
|-------------|-----------|--------|--------------|
| **Hub** | Camada 1 (Física) | Retransmite para todas as portas | D-Link DES-1008A (descontinuado) |
| **Switch** | Camada 2 (Enlace) | Encaminha por endereço MAC | Cisco SG350-28 (GbE gerenciável) |
| **Roteador** | Camada 3 (Rede) | Roteia entre redes por IP | TP-Link Archer AX73 (Wi-Fi 6) |

![Dispositivos de Rede](dispositivos.png)

---

## 3. Meios de Transmissão

Esquema visual classificando os meios de transmissão em duas categorias, com cenário integrado de rede residencial moderna:

**Meios Guiados (com fio):**
- Par Trançado UTP/STP (Cat5e, Cat6, Cat6a) — Ethernet doméstica e corporativa
- Cabo Coaxial — TV a cabo, CCTV, redes legadas
- Fibra Óptica (monomodo / multimodo) — backbone de ISPs, FTTH, datacenters

**Meios Não Guiados (sem fio):**
- Wi-Fi IEEE 802.11 (2.4 GHz / 5 GHz / 6 GHz) — redes domésticas e corporativas
- Bluetooth IEEE 802.15.1 — periféricos e wearables pessoais
- Satélite (GEO / LEO) — zonas rurais, Starlink, backup WAN
- Infravermelho (IrDA) — controles remotos, transferências legadas

![Meios de Transmissão](meios_transmissao.png)

---

## 4. Reflexão Individual

Texto respondendo: *"Qual topologia seria mais adequada para a rede da sua residência e por quê?"*

> Consulte o arquivo [`reflexao_individual.md`](reflexao_individual.md) para ler o texto completo.

---

## Referência Bibliográfica

> TANENBAUM, Andrew S.; FEAMSTER, Nick; WETHERALL, David J.  
> **Redes de Computadores**. 6. ed. São Paulo: Bookman, 2021.  
> E-book. Disponível em: https://plataforma.bvirtual.com.br. Acesso em: 20 abr. 2026.

---

*Entrega referente à Aula 11 – Redes de Computadores*
