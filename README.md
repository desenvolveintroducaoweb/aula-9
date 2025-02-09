<!DOCTYPE html>
<head>
    <title>Formulário de Pesquisa</title>
</head>
<body>
    <h1>Formulário de Pesquisa de Satisfação</h1>
    <form method="post"action="procesar-pesquisa.html">
        <section>
            <h2>Dados Pessoais</h2>
        </section>
        <section>
            <h2>Dados de Pesquisa</h2>
            <p>
                <label form="nome">Nome:</label>
                <input type="text" id="nome"/>
             </p>
             <p>
                <label form="email"> E-mail: </label>
                <input type="email" id="email"/>
              </p>
              <p>
                <label form="telefone">Telefone: </label>
                <input type="tel" id="telefone"/>
              </p>
        </section>
        <section>
            <h2>Dados de Pesquisa</h2>
            <p>
                Numa escala de 1 a 5, indique o nivel de atendimento prestado:
                <input type="radio" id="1" name="nivel-atendimento"/>
                <label for="1">1</label>
                <input type="radio" id="2" name="nivel-atendimento"/>
                <label for="2">2</label>
                <input type="radio" id="3" name="nivel-atendimento"/>
                <label for="3">3</label>
                <input type="radio" id="4" name="nivel-atendimento"/>
                <label for="4">4</label>
                <input type="radio" id="5" name="nivel-atendimento"/>
                <label for="5">5</label>
            </p>
            <p>
                Numa escala d e 1 a 5, indique o nivel de satisfação em relação do problema:
                <input type="radio" id="1" name="nivel-resolução"/>
                <label for="1">1</label>
                <input type="radio" id="2" name="nivel-resolução"/>
                <label for="2">2</label>
                <input type="radio" id="3" name="nivel-resolução"/>
                <label for="3">3</label>
                <input type="radio" id="4" name="nivel-resolução"/>
                <label for="4">4</label>
                <input type="radio" id="5" name="nivel-resolução"/>
                <label for="5">5</label>
            </p>
            <p>
                <Isabel for="departamento">Departamento de atendimento:</Isabel>
                <select>
                    <option>Marketing</option>
                    <option>Financeiro</option>
                    <option>Comercial</option>
                    <option>Logistica</option>
                    <option>Recursos Humanos</option>
                </select>
            </p>
            <p>
                <input type="checkbox" id="compartilhar-dados" />
                <label for="compartilhar-dados">Autorizo compartilhamento de dados com terceiros</label>
            </p>
        </section>
        <input type="submit" value="Enviar" />
     </form>
</body>
<html>
