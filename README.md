# FlutterWeather

Um aplicativo simples de previsão do tempo criado com [Flutter](https://flutter.dev/) e [Dart](https://dart.dev/), usando a API do [OpenWeatherMap](https://openweathermap.org/).

## Funcionalidades
- Localização automática do usuário
- Pesquisa de local
- Previsão horária e para os próximos 7 dias

## Como Executar
1. Crie uma conta em [OpenWeatherMap](https://openweathermap.org/) e obtenha sua chave de API em https://home.openweathermap.org/api_keys.
2. Clone o repositório:
   ```sh
   git clone https://github.com/ArizArmeidi/FlutterWeather.git
   ```
3. Instale as dependências:
   ```sh
   flutter pub get
   ```
4. No arquivo **lib/provider/weatherProvider.dart**, cole sua chave de API na variável `apiKey`:
   ```dart
   String apiKey = 'Cole Sua Chave de API Aqui';
   ```
5. Execute o aplicativo no seu ambiente de desenvolvimento Flutter.