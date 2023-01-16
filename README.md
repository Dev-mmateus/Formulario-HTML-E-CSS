
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" type="text/css" href="formulario.css" media="screen">
    </title>Cadastro</title>
</head>

<body>
    <div class="campo">
    <h1 id= "titulo"> Cadastro de DEV'S</h1>
    <p id="subtitulo"> Complete suas informações</p>
    </div>
    <form>
        <fieldset class="grupo">
            <div class="campo">
                <label for="nome">Nome</label>
                <input type="text" name="nome" id="nome" required>
            </div>
            <div class="campo">
                <label for="sobrenome"> Sobrenome</label>
                <input type="text" name="Sobrenome" id="sobrenome" required>
           </div>
           </fieldset>
           <div class="campo">
            <label for="email"> Email</label>
            <input type="email" name="email" id="email" required>
           </div>

        <div class="campo">
           <label> De qual lado da aplicação você desenvolve?</label>
        
           <label>
            <input type="radio" name="devweb" value="Front-end"> Front-end         
         </label>
         <label>
            <input type="radio" name="devweb" value="backend">Back-end 
        </label>
        <label>
            <input type="radio" name="devweb" value="fullstack">FullStack
        </label>
        </div>
        <div class="campo">
            <label for="senioridade"> senioridade</label>
            <select id="senioridade">
                <option selected disabled value="">senioridade</option>
                <option>Junior</option>
                <option>Pleno</option>
                <option>Senior</option>
            </select>
        </div>
        <fieldset class="grupo">
            <div id="check">
                <label> Selecione as tecnologias que você conhece:</label><br><br>
                <input type="checkbox" id="tecnologia1" name="tecnologia1" value="HTML">
                <label for="tecnologia1">HTML</label>
                <input type="checkbox" id="tecnologia2" name="tecnologia2" value="CSS">
                <label for="tecnologia2">CSS</label>
                <input type="checkbox" id="tecnologia3" name="tecnologia3" value="JavaScript">
                <label for="tecnologia3">JavaScript</label>
                <input type="checkbox" id="tecnologia4" name="tecnologia4" value="Python">
                <label for="tecnologia4">Python</label>
                <input type="checkbox" id="tecnologia5" name="tecnologia5" value="C#">
                <label for="tecnologia5">C#</label>
                <input type="checkbox" id="tecnologia6" name="tecnologia6" value="Java">
                <label for="tecnologia6">Java</label>
                <input type="checkbox" id="tecnologia7" name="tecnologia7" value="PHP">
                <label for="tecnologia7">PHP</label>
                </div>
            </fieldset>
            </div><br>
    <div class="campo">
        <labe>Conte um pouco de sua experiência:</labe>
        <textarea row="9" style="width: 26em" id="experiencia" name="experiencia" ></textarea>
    </div>
    <button class="botao" type="submit">Concluído</button>
</fieldset>
    </form>
    
</body>
</html>
