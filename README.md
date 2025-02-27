# 🚀 Fine-Tuning de Modèles Multimodaux sur Données Textuelles
Ce dépôt fournit les ressources et le code pour affiner des modèles multimodaux uniquement 
avec des données textuelles. L'objectif est de spécialiser la partie langage sans altérer 
les capacités de traitement d'images du modèle. <br/>

# 📌 Contexte
Les modèles multimodaux, capables d'analyser à la fois du texte et des images, sont de plus en plus 
utilisés. Cependant, dans certains cas d'usage, il est nécessaire d'améliorer uniquement leur capacité 
de traitement du texte sans affecter leur compétence sur les images. Ce projet vise donc à affiner 
la partie textuelle de modèles multimodaux, en utilisant des techniques d'entraînement avancées 
telles que PEFT et QLoRA. <br/>

# 🏗 Modèles étudiés
Nous avons travaillé sur trois modèles multimodaux : <br/>

- Llava-1.6-Vicuna-13B <br/>
Checkpoint : llava-hf/llava-v1.6-vicuna-13b-hf <br/>
Fine-tuning avec PEFT et bitsandbytes <br/>
- Pixtral-12B <br/>
Checkpoint : unsloth/Pixtral-12B-2409 <br/>
Fine-tuning avec Unsloth <br/>
- Llama-3.2-11B-Vision <br/>
Checkpoint : unsloth/Llama-3.2-11B-Vision-Instruct <br/>
Fine-tuning avec Unsloth <br/>

# 🔚 Conclusion
Ce projet démontre la faisabilité d’un fine-tuning ciblé sur la partie textuelle des modèles multimodaux. 
En utilisant des techniques avancées d'entraînement, nous avons réussi à améliorer la compréhension 
et la génération de texte tout en conservant l’intégrité des autres fonctionnalités du modèle. <br/>
Les notebooks disponibles dans ce dépôt détaillent le processus d'entraînement pour chaque modèle, 
permettant une reproduction et une adaptation faciles à d'autres cas d'utilisation. <br/>

# 📜 Licence
Ce projet est disponible sous la licence MIT.
