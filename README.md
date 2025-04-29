import 'dart:io';

main() {
  print('ola! Qual o seu nome? ');
  final String? name = stdin.readLineSync();

  print(
    'ola '
    '$name',
  );

  print('Qual a sua idade? ');
  int? idade = int.parse(stdin.readLineSync()!);

  print(
    'voce tem '
    '$idade'
    ' anos',
  );

  print('agora vamos responder algumas questoes?');
  print('A selecao brasileira tem quantos titulos mundiais?');
  print('a) 4 titulos\nb) 5 titulos\nc) 1 titulos\nd) 3 titulos\n');
  String questao1 = 'b';
  String? respostaQuestao1 = stdin.readLineSync()!;

  if (respostaQuestao1 == questao1) {
    print('resposta correta');
  } else {
    print('resposta errada');
  }

  print('Questao 2, qual a capital do brasil?');
  print('a) Rio de Janeiro\nb) Sao Paulo\nc) Belo Horizonte\nd) brasilia\n');
  String questao2 = 'd';
  String? respostaQuestao2 = stdin.readLineSync()!;
  if (respostaQuestao2 == questao2) {
    print('resposta correta');
  } else {
    print('resposta errada');
  }

  print('questao 3, qual e a galaxia mais proxima do da VIA LACTA? ');
  print(
    'a) Via lacta\nb) Galaxia ana do cao maior\nc) galaxia de andromeda\nd) galaxia do triangulo)',
  );
  String questao3 = 'b';
  String? respostaQuestao3 = stdin.readLineSync()!;
  if (respostaQuestao3 == questao3) {
    print('resposta correta');
  } else {
    print('resposta errada');
  }

  print(
    'questao 4, Pedro tem 30 anos, se ele tivesse nascido 10 anos atras, quantos anos ele teria?',
  );
  print('a) 20\nb) 55\nc) 10\nd) 60\n');
  String questao4 = 'c';
  String? respostaQuestao4 = stdin.readLineSync()!;
  if (respostaQuestao4 == questao4) {
    print('resposta correta');
  } else {
    print('resposta errada');
  }
}
