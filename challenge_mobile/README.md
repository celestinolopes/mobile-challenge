# Dr.Cash - Mobile Challenge  




## Documentação

Este projeto foi criando utilizando o Flutter & Dart.<br>

## Instrução para rodar o projeto

### 1 - Faça um clone do repositório
```bash
git clone https://github.com/celestinolopes/mobile-challenge.git
```

### 2 - Instale as dependencias do flutter
```bash
flutter pub get
```
### 3 - Conecte o seu celular/imulador

### 4 - Inicie a aplicação

```bash
flutter run
```

### <b>FLUTTER </b><br>
A versão do Flutter usado foi:
- ✅ Flutter v.2.10.3

### <b>TECNOLOGIAS UTILIZADAS</b></br>
 Abaixo encontram-se alguns dos principais packages que foram utilizados no app.
- ✅ Dio 
- ✅ Provider
- ✅ Faker
- ✅ Mockito
- ✅ DartZ
- ✅ CachedNetWorkImage
 ### <b>PRINCÍPOS SEGUIDOS</b></br>
 
 - ✅ Clean Architecture
 - ✅ TDD
 - ✅ SOLID
 - ✅ CLEAN CODE
   <br>
### Arquitetura do Projeto

O Projeto utiliza o [Clean Architecture](https://blog.cleancoder.com/uncle-bob/2012/08/13/the-clean-architecture.html). O Projeto foi dividido em dois módulos/features que são:
<br>
-  Authentication (Modulo responsável pela autenticação do usuários)
- Home (Modulo para listar as clinícas)
<br><br>

### <b>ESTRUTURA DE ARQUIVOS</b>
 <br>Em cada módulo encontramos a seguinte estrutura de arquivos:
 </br>

 <img src="https://raw.githubusercontent.com/celestinolopes/mobile-challenge/main/challenge_mobile/assets/images/folder_structure.PNG">

 ## Explicação da estrutura de arquivos

 ### <b>Domain</b>:
 O domínio  é a camada interna do aplicativo, Ele conterá apenas a  lógica de negócios  principal ( casos de uso ) e  objetos de negócios  ( entidades ). Deve ser totalmente  independente de todas as outras camadas.
 <br>
 - <b>Nota</b>: Casos de uso  são classes que encapsulam toda a lógica de negócios de um caso de uso específico do aplicativo

### <b>Data:</b>
A  camada de dados  consiste em uma  implementação de Repositório  (o contrato vem da  camada de domínio ) e  fontes de dados  - uma geralmente é para obter dados remotos (API) e a outra para armazenar em cache esses dados. 

### <b>Repository:</b>
O repositório é onde você decide se deseja retornar dados atualizados ou armazenados em cache, quando armazená-los em cache e assim por diante.

### <b>Presentation</b>
Como o nome sugere, este é responsável por mostrar os dados ao usuário (Telas, widgets , etc).

## Testes Unitários

O projecto foi feito usando as boas práticas de TDD 
<br>
Para rodar todos  os testes para usar a interface do vsCode.
<br><br>
<img src="https://raw.githubusercontent.com/celestinolopes/mobile-challenge/main/challenge_mobile/assets/images/test_project.PNG">

## Injeção de Dependência

Para a injenção de dependências e gerenciamento de estado foi o utizado o [Provider](https://pub.dev/packages/provider)
<br>
# <b>FUTURO</b>

- Adicionar um sistema de cache para que o app possa funcionar quando estiver offline;
- Adicionar um campo de busca;
- Filtrar clinícas pelo tipo serviço, localização, etc;
-





