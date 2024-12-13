**1. Instalar Python e Pip:  **
  Download e instalação do Python: Baixe a versão mais recente do Python em python.org.
  Adicionar ao PATH: Durante a instalação, marque a opção para adicionar o Python ao PATH.
  Verificar a instalação:
    primeiro comando no cmd:  python --version
    segundo comando no cmd:  pip --version
                          
**2. Instalar o WAMP Server:  **
  Download e instalação: Baixe o WAMP Server em wampserver.com.
  Configuração do MySQL: Certifique-se de que o MySQL esteja funcionando no WAMP, e que o MySQL Workbench esteja configurado corretamente para se conectar ao seu servidor local.

**3. Instalar o MySQL Connector para Python:  **
  Instalar MySQL Connector:  pip install mysql-connector-python
    
**4. Instalar o OpenCV (cv2):  **
  Instalar OpenCV para captura de vídeo e processamento de imagens:  pip install opencv-python

**5. Instalar a biblioteca dlib:  **
  Instalar o dlib: O dlib é uma dependência do face_recognition. Como é necessário compilar com CMake, vamos precisar de algumas ferramentas extras.
  Instalar CMake e Visual Studio Build Tools:
  Baixe e instale CMake através do site:  https://cmake.org
  Baixe o Visual Studio Build Tools (necessário para compilar o dlib no Windows):  https://visualstudio.microsoft.com/pt-br/visual-cpp-build-tools/
  Instalar dlib: pip install dlib

**6. Instalar a biblioteca face_recognition:  **
  Instalar face_recognition para reconhecimento facial:  pip install face_recognition

**7. Instalar NumPy e Pillow:  **
  Instalar NumPy:  pip install numpy
  Instalar Pillow (para manipulação de imagens):  pip install Pillow

**8. Instalar dotenv (para carregar variáveis de ambiente):  **
  Instalar dotenv:  pip install python-dotenv

**10. Testar o Sistema:  **
  Verificar as dependências: Após a instalação das bibliotecas, rode o seguinte comando para verificar se tudo foi instalado corretamente:  pip freeze
