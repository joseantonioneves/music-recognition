# Music-Recognition

Aplicativo de reconhecimento de música com interface gráfica em Windows Forms, desenvolvido em C#. Ele utiliza bibliotecas externas como NAudio (para manipulação de áudio), DBreeze (para banco de dados) e Newtonsoft.Json (para manipulação de JSON).

A estrutura principal do projeto está na pasta MusicRecognition Project, contendo:

* Interface gráfica: Frontend (formulário principal) e WaveForm (visualização de forma de onda).
* Gerenciamento de áudio: AudioManager.
* Gerenciamento de banco de dados: DatabaseManager.
* Visualização customizada de áudio: CustomWaveViewer.

## O fluxo básico do programa é:

1. O usuário interage com a interface Frontend.
2. O áudio é capturado e processado pelo AudioManager.
3. Os dados de áudio e resultados são armazenados/consultados via DatabaseManager.
4. A forma de onda e espectro são exibidos usando WaveForm e CustomWaveViewer.

O projeto é gerenciado pelo arquivo de solução MusicRecognition Project.sln e o projeto C# está em MusicRecognition Project.csproj.