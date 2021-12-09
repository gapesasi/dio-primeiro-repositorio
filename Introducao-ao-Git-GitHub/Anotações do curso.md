##                                             GIT

#### Usuário

- Definir E-mail - **git config --global user.email < e-mail > **
- Definir Nome - **git config --global user.name < nome >**

#### Comandos Base

- Iniciar o GIT - **git init**
- Iniciar Versionamento - **git add < nomeArquivo > // git add * // git add .**
- Iniciar Commit - **git commit**
- Estado de arquivos - **git status**
- Add origem remota - **git remote add < nomerep ex:origin > < link GitHub >**
- Empurrar repositório - **git push < nomerep> (master/main...)**
- Puxar repositório - **git pull < nomerep> (master/main...) **

#### Comandos de Navegação

- Listar - **dir**
- Navegar - **cd < nome >**
- Retroceder - **cd ..**
- Criar Pasta - **mkdir < nome >**
- Deletar pasta - **rmdir < nome >**
- Devolver o digitado - **echo < digitado >**
- Redirecionar de fluxo - **> < nome recebedor de fluxo >**
- Deletar arquivo - **del < nome >**
- Mover - **mv < nome1 > < nome2 >**
- Clonar arquivo - **git clone < url >**

#### Extensões

- Markdown - **.md**

#### Flags

- Entender texto - **--stdin**
- Mostrar Ocultos - **-a**
- Definir como Global - **-global**
- Acompanha git commit - **-m**

#### Atalhos

- Limpar a tela - **Crtl+L**
- Completar texto - **TAB**                        

##                                                                                  Chaves SSH e Token

#### Chave SSH 

1. **ssh-keygen - t ed25519 -C < email >**
2. **cad id_ed25519.pub**
3. **eval $(ssh -agent -s)**
4. **ssh-add id_ed25519**
5. **git clone "SSH"**

#### Token

1. **Github**
2. **Settings**
3. **"Developer Settings"**
4. **Personal acess tokens** 
5. **Create new Token**