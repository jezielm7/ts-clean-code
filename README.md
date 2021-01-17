# Clean Code Principles

## __Variáveis__

### 1. Sempre deixar suas variáveis o mais descritivas possíveis. 
### 2. Não abreviar nome de variáveis.
### 3. Evitar redundâncias.

<br/>

## __Funções__

### 1. Sempre deixar suas funções o mais descritivas possíveis.
### 2. Cada função deve ter apenas uma responsabilidade.
### 3. Sempre começar funções com verbo.

<br/>

## __Comentários__

### 1. Na maioria das vezes mais atrapalhará do que ajudará.
### 2. Comentários são desatualizados. 

<br/>

## __Comentários Úteis__

### 1. Para descrever um bug.
### 2. Para descrever uma regra de negócio. 

<br/>

## __Números Mágicos__

### 1. Sempre declarar os números.

<br/>

# Anti Pattern

## __Definição__

### Um padrão de código ruim.

<br/>

## Exemplos

### **- Prop Drilling (React)**
    Resolução: É quando uma propriedade atravessa vários componentes.

### **- Mal uso das Keys (React)**
    Resolução: A key deve ser única e previsível.

### **- Componentes que retornam múltiplos componentes**
    Resolução: Crie micro componentes.

<br/>

# Code Smell (Código Sujo)

## Exemplos

### **- Múltiplos níveis de indentação**
    Resolução: Uso de Early Return. 

### **- Funções que recebem muitos parâmetros**
    Resolução: Dividir a função em funções menores.

### **- Funções muito longas**
    Resolução: Dividir a função em funções menores.

<br/>

# Princípios da Programação

## __DRY__ (Don't repeat yourself)

### Abstrair o código comum com alteração apenas dos parâmetros.

<br/>

## __KISS__ (Keep it simple stupid)

### Manter o código o mais estupidamente simples possível.

<br/>

## __YAGNI__ (You ain't gonna need it)

### Não adicionar ferramentas desnecessárias no código.

<br/>

# Dica Bônus

## 1. Sempre usar linters na aplicação.
## 2. Código Limpo é um código de fácil compreensão.
