# Arquivos de linguagem do Laravel 7.x - Português do Brasil

O arquivo README.md foi baseado no do repositório [enniosousa/laravel-5.5-pt-BR-localization](https://github.com/enniosousa/laravel-5.5-pt-BR-localization). A tradução foi a partir dos arquivos originais do Laravel na versão 7.x.

## Instalação

1. Clonar este repositório na pasta `resources/lang/` do seu projeto
  ```
  $ cd resources/lang/
  $ git clone https://github.com/cleitonsb/laravel-7.x-pt-BR-localization.git ./pt-BR
  ```

  Você pode remover o diretório .git caso deseje incluir e versionar os arquivos deste projeto no seu repositório.

  ```
  $ rm -r pt-BR/.git/
  ```

  Se você estiver usando Windows Server ou Azure
  ```
  rd /s /q pt-BR/.git/
  ```

2. Configurar o Framework para utilizar 'pt-BR' como linguagem padrão
  ```
  // No arquivo config/app.php localize e altere
  'locale' => 'pt-BR',
  ```
  
## Localização para outras versões do Laravel
  
* [Laravel 5.4](https://github.com/Leomhl/laravel-5.4-pt-br-localization)
* [Laravel 5.5](https://github.com/enniosousa/laravel-5.5-pt-BR-localization)
* [Laravel 5.6](https://github.com/lucascudo/laravel-5.6-pt-BR-localization)
* [Laravel 5.7](https://github.com/lucascudo/laravel-5.7-pt-BR-localization)
