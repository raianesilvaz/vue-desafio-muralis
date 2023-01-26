
<template>
    <div class="formulario">
        <h1>Cadastro de Ingressantes</h1>
        <form>
            <label>Nome
                <input />
            </label>

            <label>Curso
                <select name='Curso'>
                    <option value="">Selecione</option>
                    <option value="1">Matemática</option>
                    <option value="2">Letras</option>
                    <option value="3">Geogradia</option>
                </select>
            </label>

            <label>Estado
                <select name='Estado'>
                    <option value="">Selecione</option>
                    <option value="1">São Paulo</option>
                    <option value="2">Rio de Janeiro</option>
                    <option value="3">Minas Gerais</option>
                </select>
            </label>

            <label>Cidade
                <select name='Cidade'>
                    <option value="">Selecione</option>
                    <option value="1">Mogi das Cruzes</option>
                    <option value="2">Suzano</option>
                    <option value="3">Poá</option>
                    <option value="4">Angra dos Reis</option>
                    <option value="5">Niterói</option>
                    <option value="6">Itaboraí</option>
                    <option value="7">Belo Horizonte</option>
                    <option value="8">Monte Azul</option>
                    <option value="9">Muzambinho</option>
                </select>
            </label>
            <button class='button1' type='submit'>Voltar</button>
            <button class='button2' type='submit'>Gravar</button>
        </form>
    </div>
</template>


<style>
form {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    gap: 50px;
}

.formulario{
    border: 2px solid rgb(25, 69, 136);
    border-radius: 10px;
    height: 470px; 
    width: auto;
}

label {
    display: flex;
    flex-direction: column;
}

h1{
    position: relative;
    border: 1px solid rgb(27, 68, 124);
    border-radius: 8px;
    height: 40px;
    font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
    font-size: medium;
    background-color: rgb(63, 105, 165);
    color: aliceblue;
    display: flex;
    justify-content: center;
    align-items: center;
    margin-top: 0px;    
}

select{
    border-radius: 5px;
    border: 1px solid rgba(20, 68, 133, 1);
    height: 25px;
    width: 320px;
}

input{
    border-radius: 5px;
    border: 1px solid rgba(20, 68, 133, 1);
    height: 25px;
    width: 300px;   
}

.button1 {
    align-items: center;
    justify-content: center;
    width: 85px;
    height: 35px;
    background-color: rgba(223, 226, 12, 0.815);
    border: 1px solid yellow;
    border-radius: 8px;
    font-weight: bold;
    cursor: pointer;
    color: whitesmoke;
    position: relative;
    right: 102px;
    top: -20px;   
}

.button2{
    align-items: center;
    justify-content: center;
    width: 85px;
    height: 35px;
    background-color: rgb(52, 196, 51);
    border: 1px solid rgb(34, 167, 34);
    border-radius: 8px;
    font-weight: bold;
    cursor: pointer;
    color: whitesmoke;
    position: relative;
    right: -102px;
    top: -104px;
}
</style>