# Practica-examen-final

saber que una matriz bi dimension como es por ejemplo la de argumentos "**argv"
se puede tratar de dos formas *argv[i], argv[i]++, argv[i][c].

como en esta funcion 
int	main(int argc, char **argv)
{
	if (argc > 1)
		while (*argv[argc - 1])
			write(1, argv[argc - 1]++, 1);
	write(1, "\n", 1);
	return (0);
}
. en el caso de argc se puede usar para imprimir ultimo parametro como se ve

