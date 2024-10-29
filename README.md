Aqui está a documentação para o projeto com a **NASA API** no mesmo formato:


# Dashboard da NASA com [Reactjs e Vite](https://pt.vitejs.dev/guide/)

O commit inicial deve incluir as configurações básicas do Reactjs com Vite:
```bash
git add .
git commit -m "ADS-init: <sua_matricula> Reactjs-vite"
```

### Objetivo do INIT
Nessa etapa, o projeto deve ser iniciado do zero para garantir um histórico de evolução completo. A escolha do repositório é livre, mas o histórico de commits e o código-fonte devem estar visíveis para avaliação.

# Iniciando o Projeto
Todos os arquivos criados devem conter a data, nome e matrícula, além de uma breve descrição sobre o documento.

### Exemplo de Documentação em Arquivos
```js
/**
 * Nome do arquivo: exemplo.js
 * Data de criação: 30/04/2024
 * Autor: João Silva
 * Matrícula: 123456
 *
 * Descrição:
 * Este arquivo JavaScript é responsável por implementar as funcionalidades
 * de interação do usuário com a interface gráfica do módulo de visualização da NASA.
 * Aqui são tratados eventos de cliques, validações de entrada e comunicação
 * com a API da NASA para exibir a imagem astronômica do dia.
 */
```

---

### Funcionalidades do Dashboard da NASA

# Imagem desktop
![image](https://github.com/user-attachments/assets/bfce0907-52a1-4389-a54e-8f7e74cca48d)

# Imagem Mobile

![Captura de tela 2024-10-29 - 13 33 52](https://github.com/user-attachments/assets/f473d34c-ee8a-4b11-97bc-54f5fc4306cb)

1. **Exibição da Imagem Astronômica do Dia**
   - A página exibe informações sobre a imagem astronômica do dia, incluindo:
     - **Título da Imagem**: Nome da imagem fornecido pela NASA.
     - **Imagem**: A imagem astronômica principal do dia.
     - **Descrição**: Uma breve explicação sobre a imagem e o que ela representa.
   - **Exemplo de Commit**:
     ```bash
     git commit -m "ADS-imagem_do_dia: <sua_matricula> Reactjs-vite"
     ```

2. **Filtro de Data**
   - Um campo de data permite ao usuário selecionar uma data específica para visualizar a imagem daquele dia.
   - Ao clicar no botão "Buscar", a aplicação exibe a imagem e a descrição para a data escolhida.
   - **Exemplo de Commit**:
     ```bash
     git commit -m "ADS-filtro_data: <sua_matricula> Reactjs-vite"
     ```

3. **Layout Responsivo**
   - O layout ajusta automaticamente a exibição da imagem e da descrição para diferentes tamanhos de tela:
     - **Telas grandes**: A imagem é exibida à esquerda e a descrição à direita.
     - **Telas pequenas**: A imagem e o texto são exibidos em uma coluna, para uma melhor experiência em dispositivos móveis.
   - **Exemplo de Commit**:
     ```bash
     git commit -m "ADS-layout_responsivo: <sua_matricula> Reactjs-vite"
     ```

4. **Carregamento Dinâmico dos Dados**
   - A aplicação faz uma chamada à API da NASA para buscar a imagem astronômica do dia ou de uma data específica.
   - Enquanto os dados estão sendo carregados, uma mensagem "Carregando imagem..." é exibida para informar o usuário.
   - Em caso de erro, uma mensagem é exibida para o usuário tentar novamente mais tarde.
   - **Exemplo de Commit**:
     ```bash
     git commit -m "ADS-carregamento_dinamico: <sua_matricula> Reactjs-vite"
     ```

---

### Exemplo de Consulta à NASA API

Abaixo está um exemplo de configuração da URL para buscar a imagem astronômica do dia na API da NASA. Esta configuração especifica o uso da chave da API (`api_key`) e permite filtrar pela data, se fornecida.

```json
"https://api.nasa.gov/planetary/apod",
{
  params: {
    api_key: "DEMO_KEY",
    date: "YYYY-MM-DD"
  }
}
```

---

### Histórico de Commits

Para garantir o acompanhamento do desenvolvimento e manutenção do projeto, cada funcionalidade deve ser devidamente commitada no Git, conforme os exemplos de commits fornecidos para cada funcionalidade. Abaixo, estão as instruções gerais para versionamento no Git.

1. **Configurações Iniciais do Projeto**:
   - Adicione o conteúdo inicial do projeto:
     ```bash
     git add .
     git commit -m "ADS-init: <sua_matricula> Reactjs-vite"
     ```

2. **Adicionando Funcionalidades e Melhorias**:
   - Para cada nova funcionalidade ou atualização, siga o padrão de nomenclatura conforme mostrado:
     ```bash
     git commit -m "ADS-nome_da_funcionalidade: <sua_matricula> Reactjs-vite"
     ```
   - Exemplos adicionais:
     - **Filtro de Data**: `git commit -m "ADS-filtro_data: <sua_matricula> Reactjs-vite"`
     - **Estilização Responsiva**: `git commit -m "ADS-estilizacao_responsiva: <sua_matricula> Reactjs-vite"`
     - **Tratamento de Erros**: `git commit -m "ADS-tratamento_erros: <sua_matricula> Reactjs-vite"`
     - **Melhorias de Layout**: `git commit -m "ADS-melhorias_layout: <sua_matricula> Reactjs-vite"`

---

### Estrutura do Projeto

Certifique-se de que todos os arquivos e funcionalidades estão devidamente documentados com a data, o nome do autor e a matrícula, para facilitar a revisão e manutenção do código-fonte. Seguindo as orientações e exemplos de commits, o projeto deverá estar bem organizado e apresentará um histórico claro de desenvolvimento.




## Observação
Será zerado caso os critérios de commit não sejam seguidos, se os arquivos criados pelo autor não contiverem suas credenciais ou no caso de plágio.

___

### Datas e Prazos
A data de entrega e apresentações está definida para o período de **29/10 a 28/11**. Recomendo que concluam suas tarefas o mais cedo possível, preferencialmente antes do dia 28, para evitar conflitos de última hora, atrasos nas notas ou quaisquer surpresas desagradáveis.
