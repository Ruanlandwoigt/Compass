# Fundamentos do teste de software (Back-End)


## Tipos de Testes

### 1. Testes Unitários

- Testam unidades individuais de código (geralmente funções ou métodos)
- Isolam a funcionalidade específica sendo testada

### 2. Testes de Integração

- Verificam a interação entre diferentes componentes ou módulos
- Garantem que as partes do sistema funcionem corretamente juntas

### 3. Testes Funcionais

- Avaliam se o sistema atende aos requisitos funcionais especificados
- Focam no comportamento do sistema do ponto de vista do usuário
- Geralmente são testes de caixa preta

### 4. Testes de Desempenho

- Medem a velocidade, escalabilidade e estabilidade do sistema
- Incluem testes de carga, estresse e resistência

### 5. Testes de Segurança

- Identificam vulnerabilidades e riscos de segurança
- Incluem testes de penetração, análise de código estático e verificação de conformidade

### 6. Testes de Usabilidade

- Avaliam a experiência do usuário durante o uso do sistema
- Incluem testes de usabilidade, acessibilidade e experiência do usuário

### 7. Testes de Aceitação

- Verificam se o sistema atende aos requisitos de aceitação definidos
- Geralmente são testes manuais realizados por especialistas

## Ferramentas Populares para Testes Back-End

- JUnit (Java)
- pytest (Python)
- Mocha (Node.js)
- RSpec (Ruby)
- PHPUnit (PHP)

## Pirâmide de Testes

A pirâmide de testes é um conceito que ilustra a proporção ideal de diferentes tipos de testes em um projeto de software. A estrutura da pirâmide é a seguinte:


      ╱╲
  End-to-End
    ╱────╲
   ╱ Inte-╲
  ╱ gration╲
 ╱──────────╲
╱   Unit     ╲
──────────────


### 1. Base: Testes Unitários

- Formam a base da pirâmide
- São os mais numerosos e rápidos de executar
- Testam componentes individuais do código
- Devem cobrir a maior parte da lógica de negócios

### 2. Meio: Testes de Integração

- Menos numerosos que os testes unitários
- Verificam a interação entre diferentes componentes
- Podem incluir testes de API e de serviços

### 3. Topo: Testes de Interface do Usuário (UI) / Testes End-to-End (E2E)

- Menor quantidade de testes
- Mais lentos e complexos de manter
- Simulam o comportamento do usuário final
- Testam o sistema como um todo



