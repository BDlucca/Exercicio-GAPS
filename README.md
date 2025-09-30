# Construcao-de-uma-casa

```mermaid
gantt
  title Construção de uma casa
dateFormat YYYY-MM-DD
section Seçao 1
Planejamento e aprovaçoes:active, a1, 2025-08-28, 20d
section Seçao 2
Preparaçao do terreno:a2, after a1, 10d
section Seçao 3
Escavaçao:a3, after a2, 15d
Fundaçao:a4, after a2, 30d
section Seçao 4
 Instalaçoes:a5, after a4, 20d
section Seçao 5
Acabamento Interno:a6,after a5, 25d
Acabamento Externo:a7, after a6, 15d
section Seçao 6
Inspeçao final:a8, after a7, 5d
```

#Crystal
```mermaid
graph TD
  subgraph Matriz
    A1["Agendamento lento:C:8"]:::branco
    B2["E-commerce fora do ar:D:20"]:::amarelo
    C4["Sistema hospitalar:V:100"]:::vermelho
    D3["Aplicativo Delivery:E:50"]:::laranja
    E2["RH Sem registros:D:35"]:::amarelo
    F3["Email Corporativo:E:40"]:::laranja
    G4["Falha de segurança:V:90"]:::vermelho
    H4["Trafego Aereo:V:100"]:::vermelho
end

classDef branco fill:#fff,      stroke:#000,  stroke-width:1px;
classDef amarelo fill:#FFD84D,  stroke:#000,  stroke-width:1px;
classDef laranja fill:#FFA233,  stroke:#000,  stroke-width:1px;
classDef vermelho fill:#E64C3C, stroke:#000,  stroke-width:1px;

```


#Atividade 2
```mermaid
gantt
title Sistema de Cadastro de Empresas Parceiras
dateFormat YYYY-MM-DD
section Inicio do Projeto
Configuração do Ambiente de Desenvolvimento: crit, a1, 2025-02-01, 15d
Criação do Banco de Dados: crit, a2, after a1, 15d
Programação do Módulo de Login: crit, a3, after a2, 20d
Programação do CRUD de Empresas: crit, a4, after a3, 20d
Implementação do Upload de Logotipo: crit, a5, after a4, 20d
Desenvolvimento dos Relatórios: crit, a6, after a5, 15d
Configuração do Painel Administrativo: crit, a7, after a6, 20d
Testes Unitários e de Integração: crit, a8, after a7, 15d
section Final do Projeto
Testes de Usabilidade com Usuários Convidados: crit, a9, after a8, 15d
Implementação Final no Servidor e Entrega ao Cliente: a10, after a9, 20d

end
```
