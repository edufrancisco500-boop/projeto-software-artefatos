class Usuario {
  nome
  email
  salvar()
}

class Sistema {
  cadastrarUsuario()
  alterarDados()
  gerarRelatorio()
  salvarArquivo()
}

Sistema --> Usuario
