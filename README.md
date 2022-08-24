## Sign Language and Static-Gesture Recognition using scikit-learn


Para usar o codigo em /dataset/gesture_recognizer1.py or the code in /dataset/pipeline_final.ipynb, faça o downlaod do arquivo Dataset.zip e extraia os dados na pasta que contrib o código acima.

Ou seja, sua estrutura de pastas deve ser:
```
/home/../../dataset
       |----gesture_recognizer1.py
       |----pipeline_final.ipynb
       |----user_3
       |----user_10
       ....
       ....
       |----user_1
              |---A0.jpg
              |---A1.jpg
              |---A2.jpg
              |---...
              |---Y9.jpg
       |----user_2
              |---A0.jpg
              |---A1.jpg
              |---A2.jpg
              |---...
              |---Y9.jpg
       |---- ...
       |---- ...
```

Usando gesture_recognizer1.py:

1. Modifique a função principal em gesture_recognizer1.py para usar a lista correta de usuários. Treine e salve o reconhecedor de gestos.

2. Depois, use o método load_model  method para carregar o objeto reconhecedor de gestos salvo anteriormente. Agora, as imagens de teste podem ser testadas usando a função recognize_gesture. 

