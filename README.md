# Model Explainability

## Vision Models (TIMM)

`resnet18` model from Hugging Face was used and model explainability was compared by running different explainability methods on 10 different Imagenet class images.

Classes are: Banana, Bucket, Cat, Envelope, Leopard, Pizza, Restaurant, Sunglass, Tank, and Volcano.

Methods used are: IG, IG w/ Noise Tunnel, Saliency, Occlusion, SHAP, GradCAM, and GradCAM++.

### Method: IG (Integrated Gradients)

<figure><figcaption>Banana</figcaption><img src="results/ig_banana.png" width="250" height="250"></figure>
<figure><figcaption>Bucket</figcaption><img src="results/ig_bucket.png" width="250" height="250"></figure>
<figure><figcaption>Cat</figcaption><img src="results/ig_cat.png" width="250" height="250"></figure>
<figure><figcaption>Envelope</figcaption><img src="results/ig_envelope.png" width="250" height="250"></figure>
<figure><figcaption>Leopard</figcaption><img src="results/ig_leopard.png" width="250" height="250"></figure>
<figure><figcaption>Pizza</figcaption><img src="results/ig_pizza.png" width="250" height="250"></figure>
<figure><figcaption>Restaurant</figcaption><img src="results/ig_restaurant.png" width="250" height="250"></figure>
<figure><figcaption>Sunglass</figcaption><img src="results/ig_sunglass.png" width="250" height="250"></figure>
<figure><figcaption>Tank</figcaption><img src="results/ig_tank.png" width="250" height="250"></figure>
<figure><figcaption>Volcano</figcaption><img src="results/ig_volcano.png" width="250" height="250"></figure>


### Method: IG w/ Noise Tunnel

<img src="results/ignt_banana.png" height="250">
<img src="results/ignt_bucket.png" height="250">
<img src="results/ignt_cat.png" height="250">
<img src="results/ignt_envelope.png" height="250">
<img src="results/ignt_leopard.png" height="250">
<img src="results/ignt_pizza.png" height="250">
<img src="results/ignt_restaurant.png" height="250">
<img src="results/ignt_sunglass.png" height="250">
<img src="results/ignt_tank.png" height="250">
<img src="results/ignt_volcano.png" height="250">


### Method: Occlusion

<img src="results/occlusion_banana.png" height="250">
<img src="results/occlusion_bucket.png" height="250">
<img src="results/occlusion_cat.png" height="250">
<img src="results/occlusion_envelope.png" height="250">
<img src="results/occlusion_leopard.png" height="250">
<img src="results/occlusion_pizza.png" height="250">
<img src="results/occlusion_restaurant.png" height="250">
<img src="results/occlusion_sunglass.png" height="250">
<img src="results/occlusion_tank.png" height="250">
<img src="results/occlusion_volcano.png" height="250">


### Method: SHAP

<img src="results/shap_banana.png">
<img src="results/shap_bucket.png">
<img src="results/shap_cat.png">
<img src="results/shap_envelope.png">
<img src="results/shap_leopard.png">
<img src="results/shap_pizza.png">
<img src="results/shap_restaurant.png">
<img src="results/shap_sunglass.png">
<img src="results/shap_tank.png">
<img src="results/shap_volcano.png">


### Method: GradCAM

<figure><figcaption>Banana</figcaption><img src="results/gc_banana.png" width="250" height="250"></figure>
<figure><figcaption>Bucket</figcaption><img src="results/gc_bucket.png" width="250" height="250"></figure>
<figure><figcaption>Cat</figcaption><img src="results/gc_cat.png" width="250" height="250"></figure>
<figure><figcaption>Envelope</figcaption><img src="results/gc_envelope.png" width="250" height="250"></figure>
<figure><figcaption>Leopard</figcaption><img src="results/gc_leopard.png" width="250" height="250"></figure>
<figure><figcaption>Pizza</figcaption><img src="results/gc_pizza.png" width="250" height="250"></figure>
<figure><figcaption>Restaurant</figcaption><img src="results/gc_restaurant.png" width="250" height="250"></figure>
<figure><figcaption>Sunglass</figcaption><img src="results/gc_sunglass.png" width="250" height="250"></figure>
<figure><figcaption>Tank</figcaption><img src="results/gc_tank.png" width="250" height="250"></figure>
<figure><figcaption>Volcano</figcaption><img src="results/gc_volcano.png" width="250" height="250"></figure>


### Method: GradCAM++

<figure><figcaption>Banana</figcaption><img src="results/gcpp_banana.png" width="250" height="250"></figure>
<figure><figcaption>Bucket</figcaption><img src="results/gcpp_bucket.png" width="250" height="250"></figure>
<figure><figcaption>Cat</figcaption><img src="results/gcpp_cat.png" width="250" height="250"></figure>
<figure><figcaption>Envelope</figcaption><img src="results/gcpp_envelope.png" width="250" height="250"></figure>
<figure><figcaption>Leopard</figcaption><img src="results/gcpp_leopard.png" width="250" height="250"></figure>
<figure><figcaption>Pizza</figcaption><img src="results/gcpp_pizza.png" width="250" height="250"></figure>
<figure><figcaption>Restaurant</figcaption><img src="results/gcpp_restaurant.png" width="250" height="250"></figure>
<figure><figcaption>Sunglass</figcaption><img src="results/gcpp_sunglass.png" width="250" height="250"></figure>
<figure><figcaption>Tank</figcaption><img src="results/gcpp_tank.png" width="250" height="250"></figure>
<figure><figcaption>Volcano</figcaption><img src="results/gcpp_volcano.png" width="250" height="250"></figure>




## Text-Generation Models from Hugging Face

Three different pretrained models from hugging face was used and same text was used to compare explainability using SHAP.

1. gpt2

![gpt2](results/gpt2.jpg)

2. gpt2-medium

![gpt2-medium](results/gpt2-medium.jpg)

3. google/flan-t5

![flan-t5](results/flan-t5.jpg)
