# Scripts.bat

Este repositório reúne uma coleção de scripts em CMD (.bat), desenvolvidos por mim para automatizar tarefas comuns e repetitivas no Windows

## 🧹 Limpeza de arquivos temporários
Scripts para remover arquivos temporários do sistema, melhorando o desempenho e liberando espaço em disco.

## 🚀 Inicialização automática de aplicativos
Scripts que configuram programas para iniciarem automaticamente após o login do usuário.

## 📦 Instalação silenciosa de aplicativos
Instalações automatizadas (silent install) de softwares populares, otimizando o processo de setup em novos dispositivos.


## 📝 Como criar um arquivo .bat

Abra o Bloco de Notas.

Escreva seus comandos normalmente, por exemplo:

 ``` @echo off ```
 ``` echo Limpando arquivos temporários... ```
 ``` del /s /q %TEMP%\* ```
 ``` exit ```

### Salve o arquivo com a extensão .bat:

- Vá em Arquivo > Salvar como...
- Em Nome do arquivo, digite: meuscript.bat
- Em Tipo, selecione: Todos os arquivos (*.*)
- Clique em **Salvar**.
- Para executar:
- Dê dois cliques no arquivo.
- Ou clique com o botão direito > Executar como administrador, se necessário.

## 🔐 Requisitos de execução

### ⚠️ Alguns scripts exigem privilégios de administrador, principalmente aqueles que:

- Acessam ou limpam C:\Windows\Temp
- Criam pontos de restauração
- Instalam aplicativos em Program Files
- Para garantir o funcionamento completo dos scripts, execute-os como administrador.

##💡 Dica

- Você pode agendar scripts para rodarem automaticamente via Agendador de Tarefas do Windows.


