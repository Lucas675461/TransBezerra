<!DOCTYPE html>
<html lang="pt-br">

<head>
    <title>
        TransBezzerra transportes LTDA.
    </title>
    <style>
        body {
            background-color: rgb(255, 255, 255);
            color: rgb(0, 0, 0);
            font-family: Verdana;
        }
    </style>
</head>

<body>
    <form>
        <fieldset id="usuário">
            <legend>Identificação</legend>
            <p><label for="cnome">Nome:<input type="text" name="tnome" id="cnome" size="20" maxlength="30"
                        placeholder="Nome completo"></label>
            </p>
            <p><label for="cEst">Estado:</label>
                <select name="tEst" id="cEst">
                    <optgroup label="Região Sudeste">
                        <option value="RJ">Rio de Janeiro</option>
                        <option value="SP">São Paulo</option>
                        <option value="MG">Minas Gerais</option>
                        <option value="ES">Espírito Santo</option>
                    </optgroup>
                    <optgroup label="Região Centro-oeste">
                        <option value="GO">Goiás</option>
                        <option value="MT">Mato Grosso</option>
                        <option value="MS">Mato Grosso do Sul</option>
                    </optgroup>
                    <optgroup label="Região Norte">
                        <option value="AC">Acre</option>
                        <option value="AP">Amapá</option>
                        <option value="RR">Roraima</option>
                        <option value="AM">Amazonas</option>
                        <option value="PA">Pará</option>
                        <option value="RO">Rondônia</option>
                        <option value="TO">Tocantins</option>
                    </optgroup>
                    <optgroup label="Região Sul">
                        <option value="RS">Rio Grande do Sul</option>
                        <option value="PR">Paraná</option>
                        <option value="SC">Santa Catarina</option>
                    </optgroup>
                    <optgroup label="Região Nordeste">
                        <option value="Ma">Maranhão</option>
                        <option value="PI">Piauí</option>
                        <option value="CE">Ceará</option>
                        <option value="RN">Rio Grande do Norte</option>
                        <option value="PB">Paraíba</option>
                        <option value="PE">Pernambuco</option>
                        <option value="AL">Alagoas</option>
                        <option value="SE">Sergipe</option>
                        <option value="BA">Bahia</option>
                    </optgroup>
                </select>
            </Fieldset>
            <fieldset id="Preferências">
                <legend>Preferências</legend>
                <input type="radio" name="tpre" id="cFrutas" /><label for="cFrutas">Frutas</label><br>
                <input type="radio" name="tpre" id="cLegumes" /><label for="cLegumes">Legumes</label><br>
                <input type="radio" name="tpre" id="cVerduras" /><label for="cVerduras">Verduras</label><br>
                <p><label for="cEst">Produtos:</label>
                    <select name="tpro" id="cpro">
                        <optgroup label="Frutas">
                            <option value="Mamão">Mamão</option>
                            <option value="Laranja">Laranja</option>
                            <option value="Manga">Manga</option>
                            <option value="Maçã">Maçã</option>
                            <option value="Banana">Banana</option>
                            <option value="Melão">Melão</option>
                            <option value="Abacate">Abacate</option>
                            <option value="Abacaxi">Abacaxi</option>
                        </optgroup>
                        <optgroup label="Legumes">
                            <option value="Feijão">Feijão</option>
                            <option value="Arroz">Arroz</option>
                            <option value="Pimentão">Pimentão</option>
                            <option value="Abobrinha">Abobrinha</option>
                            <option value="Batata">Batata</option>
                            <option value="Cenoura">Cenoura</option>
                            <option value="Cebola">Cebola</option>
                            <option value="Milho">Milho</option>
                        </optgroup>
                        <optgroup label="Verduras">
                            <option value="Acelga">Acelga</option>
                            <option value="Alface">Alface</option>
                            <option value="Alho-Poró">Alho-Poró</option>
                            <option value="Coentro">Coentro</option>
                            <option value="Escarola">Escarola</option>
                            <option value="Repolho">Repolho</option>
                            <option value="Rúcula">Rúcula</option>
                            <option value="Salsa">Salsa</option>
                        </optgroup>
                    </select>
                </p>
                <label for="Data">Informe um dia de sua preferência para entregarmos o(s) Produtos(s)</label><br>
                <input type="date" id="data" name="Dpre"><br>
                <label for="Hora">Informe um Horário para efetuarmos a entrega</label><br>
                <input type="time" id="Hora" name="Dpre">
            </fieldset>
            <fieldset id="Mensagem">
                <legend>Mensagem do Usuário</legend>
                <p>Deixe aqui a sua opinião com relação ao atendimento, sua opinião é muito importante para podermos cada vez mais melhorar o nosso atendimemto</p>
                <input type="textarea" name="Tmen" id="Cmen">
                <p><label for="cUrg">Deixe aqui a sua nota:</label>
                    0<input type="range" name="tUrg" id="cUrg" min="0" max="10" step="2" />10</p>
            </fieldset>
    </form>
</body>

</html>
