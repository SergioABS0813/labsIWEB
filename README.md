# labsIWEB

## Menú para labs

        System.out.println("+++++++++++++++++++++++++++++++");
        System.out.println("|          Menú               |");
        System.out.println("|  1 <- Registrar Nuevo Grupo |");
        System.out.println("|  2 <- Listar Nueva Persona  |");
        System.out.println("|  3 <- Listar Conciertos     |");
        System.out.println("|  9 <- Salir                 |");
        System.out.println("+++++++++++++++++++++++++++++++");
## FOR para cantidad de caracteres de un arreglo

        String nombreGrupo = "sergio andre bustamante salcedo";
        System.out.println(nombreGrupo.length()); /*Para visualizar cantidad de caracteres*/
        String arreglo[] = nombreGrupo.split(" ");
        System.out.println(arreglo[3]);
        int sum = 0;

        for (String word:arreglo) {
            sum = sum + word.length();
        }
