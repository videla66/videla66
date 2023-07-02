<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <h1>FORMULARIO</h1>
    <form>
        <fieldset>
            <legend>Información Personal</legend>
            <div>
              <label for="Nombre">Nombre:</label>
              <input type="text" name="Nombre" id="Nombre" placeholder="Nombre..."/>
           </div>

           <div>
           <label for="descripcion">Descripción</label>
           <textarea id="descripcion"></textarea>
           </div>

           <div>
              Email:
              <input type="email"/>
           </div>
           
           <div>
                Contraseña:
               <input type="password">
           </div>

           <div>
              Select:
              <select> 
                <option>hombre</option>
                <option>mujer</option>
                <option>travesti</option>
              </select>
              
           </div>
        </fieldset>

        <input type="submit" value="Enviar"/>

    </form>
    
</body>
</html>
