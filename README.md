# Projeto-busca-de-cep-com-JSF---JAX-RS

<h2>Tecnologias</h2>
JavaServer Faces == criação da página busca_cep.xhtml, onde os campos <em>input text</em> atualizam seus valores de acordo com os dados recebidos da api quando o botão aciona o método <em>buscaCep()</em> da classe <em>Cep</em> que é um ManagedBean do JSF. Também interessante notar o uso do <em>@ViewScoped</em> que mantém o estado do bean enquanto houver requisições da mesma view/página, e quando ele muda de página o estado é descartado. 
