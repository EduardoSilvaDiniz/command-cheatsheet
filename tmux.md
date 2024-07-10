# Introdução
tmux é um divisor de telas em uma janela unica de terminal
util para diversas coisas como acesso a ssh + monitoramento de logs
nvim + debuging e testes
## comandos shell
tmux = inicia o tmux e cria uma sessão
tmux ls = listar todas as sessoẽs
tmux new -s {NomeDaSessão} = inicia uma sessão com nome especifico
tmux new -s {NomeDaSessão} -d = cria uma sessão detached
tmux kill-session -t {NomeDaSessão} = mata uma sessão do nome passado
tmux kill-server = mata todas as sessoẽs

## combinação de teclas
MASTRE = CTRL(^) + b

percione a tecla mestre e depois a proxima tecla, não pode ser tudo junto, ERRADO - ctrl+b+c, Certo - Ctrl+b c
MASTRE + d = detached na sessão
MASTRE + $ = renomear a sessão
MASTRE + w = modo interativo
MASTRE + t = mostra horas

navegação entre janelas
MASTRE + c = nova janela
MASTRE + n = proxima janela
MASTRE + p = janela anterior
MASTRE + 0-9 = janela especifica

navegação entre janelas horizontal/vertical
MASTRE + " = Modo Horizontal
MASTRE + % = modo vertical
MASTRE + z = foco na janela
MASTRE + setas (cima, baixo, esquerda, direita) = troca de janela
