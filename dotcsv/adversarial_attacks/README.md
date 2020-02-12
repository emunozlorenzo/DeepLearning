# Adversarial Attack

Manipulación en el dato de entrada de la red neuronal (imperceptible al ojo humano), que lleva a la red a un resultado erroneo.

<p align="center"> 
<img src="https://github.com/emunozlorenzo/DeepLearning/blob/master/img/panda.png">
</p>

La técnica utilizada se asemeja al proceso utilizado para entrenar a una red neuronal. La forma en la que aprende una Red neuronal es a partir de la manipulación de sus parametros. Para ajustar estos parámetros se utilizan dos técnicas:

- Gradient Descent
- Backpropagation

Con estas dos técnicas, y teniendo los datos de entrada y de salido, se le pide a la red neuronal que ajuste sus parámetros para que el error sea el mínimo posible.
Por lo tanto si minimizas el error de predecir el resultado correcto, acabarás prediciendo el resultado correcto.

Con estas dos técnicas podemos realizar un ataque adversario, manipulando los datos de entrada y reajustando los parámetros para **maximizar los errores**.
Es importante que la manipulación, en el caso de imágenes, sea imperceptible al ojo humano. Por lo tanto, el goal que queremos alcanzar es el siguiente:

**Reajustar los parámetros, para maximizar el error realizando la mínima perturbación en los datos de entrada**

 
* [OPEN AI](https://www.youtube.com/redirect?redir_token=jNN-GSnHmRKaA27e9MPyDG_MEHF8MTU4MTYxNTM2MUAxNTgxNTI4OTYx&event=video_description&v=lPyogLghTKo&q=https%3A%2F%2Fblog.openai.com%2Fadversarial-example-research%2F) 
* [BERKELEY](https://www.youtube.com/redirect?redir_token=jNN-GSnHmRKaA27e9MPyDG_MEHF8MTU4MTYxNTM2MUAxNTgxNTI4OTYx&event=video_description&v=lPyogLghTKo&q=http%3A%2F%2Fbair.berkeley.edu%2Fblog%2F2017%2F12%2F30%2Fyolo-attack%2F) 
* [ADV. PATCH](https://www.youtube.com/redirect?redir_token=jNN-GSnHmRKaA27e9MPyDG_MEHF8MTU4MTYxNTM2MUAxNTgxNTI4OTYx&event=video_description&v=lPyogLghTKo&q=https%3A%2F%2Farxiv.org%2Fabs%2F1712.09665)
