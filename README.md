1. Use a pre-trained google/flan-t5-small as the model.
2. Verify if the summariza'on task works.
3. Verify if the Q&A task works.
4. Verify if English to French transla'on task works.
5. Programma'cally print the names of all the model layers and their dimensions.
6. Programma'cally print the total number of parameters/weights in this model.
7. Set the tensor in final layer (decoder.final_layer_norm.weight) to all zeros.
8. Verify if the Q&A task works aWer reseXng the weights of the above layer.
9. Replace the decoder.final_layer_norm.weight with a layer of smaller dimensions and
adjust all the dependent layers to match the dimension
10. Reload the original google/flan-t5-small model.
11. Train the model for a Q&A task that takes a context as addi'onal input along with the
ques'on. You can use SQuAD dataset (h_ps://rajpurkar.github.io/SQuAD-explorer/ )
or the smaller Topioca dataset (h_ps://mcgill-nlp.github.io/topiocqa/) . Choose an
appropriate task prefix/trigger word and jus'fy the choice.
12. Evaluate the quality of the model



The solutions for these questions are in the above notebooks. 
The solutions for  1 - 9 questions are in the assignment part-1 file and solutions for 10-12 questions are in the assignment part-2. Assignment part-2-2_epochs is the file where i have trained model for 2 epochs and Assignment part-2-4_epochs is the file where i have trained model for 4 epochs


This is the link where can you download the trained weights,
[weights_2_epochs]([URL](https://drive.google.com/drive/folders/1ax-iUx3h9HRiRrMocGOoK7ZX8-lffsyo?usp=drive_link))
[weights_4_epochs]([URL](https://drive.google.com/drive/folders/1xpqE3B-uDXbkMSxLjl9CV8vF0alSRUJx?usp=drive_link))

