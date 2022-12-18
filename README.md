# Classic MMORPG Camera And Controller

<h2>English Documentation</h2>

<b>Any suggestion or problem found, you can open an Issue in the project documentation github: https://github.com/MUN1Z/Classic-MMORPG-Camera-And-Controller</b>

<h3>CameraController Setup</h3>

The first step is to create a GameObject to represent the CameraController:

![image](https://user-images.githubusercontent.com/17263249/208306028-b068a70e-6c44-4bc8-a25e-9024fc2ea0c4.png)

The second step is to create a GameObject to represent Main Camera's Parent:

![image](https://user-images.githubusercontent.com/17263249/208306123-47d0594a-48b5-41f9-b64e-d8b0c41d048a.png)

The third step is to place the Main Camera inside the Parent Camera:

![image](https://user-images.githubusercontent.com/17263249/208306135-d8f593d5-33ec-4f5b-b3ed-9a78fb3f8d8d.png)

The fourth step is to place the CameraController.cs script in your GameObject that represents the CameraController:

![image](https://user-images.githubusercontent.com/17263249/208306248-eb3d821d-446f-4a1e-b0e2-bad383d18567.png)

![image](https://user-images.githubusercontent.com/17263249/208306182-73e98446-0645-4d65-aad1-e3a8e6d5b4fc.png)

The fifth step is to place the GameObject that represents the Parent of the Camera in the variable in the Field "Camera Parent" of CameraController.cs:

![image](https://user-images.githubusercontent.com/17263249/208306404-8a25e0d3-9f2a-4f3b-9f16-fe7226ae3031.png)

The sixth step is to configure the CollisionMark that represents the "Terrain/Floor" of your Scene:

![image](https://user-images.githubusercontent.com/17263249/208306612-ad8ad54b-5765-443f-b354-36509ee876f4.png)

And finally, you can configure the other variables according to your needs, each variable has a brief description in the C# code.

<h3>PlayerController Setup</h3>

The first step is to create a GameObject to represent the PlayerController:

![image](https://user-images.githubusercontent.com/17263249/208312133-8734dfed-7861-4c14-82fa-834bfe6157ca.png)

The second step is to create a GameObject to represent the player's direction, inside the PlayerController:

![image](https://user-images.githubusercontent.com/17263249/208312319-c48f63fa-ba67-469f-aef9-2977ae768f45.png)

The third step is to place the PlayerController.cs script in your GameObject that represents the PlayerController:

![image](https://user-images.githubusercontent.com/17263249/208312242-4a689b0b-d785-4c66-8138-4d339c24c70a.png)

![image](https://user-images.githubusercontent.com/17263249/208312331-3ba64553-9bf0-44cc-ae26-d6a8783c18f3.png)

The fourth step is to place the GameObject that represents the Direction, in the "Direction" variable of the PlayerController:

![image](https://user-images.githubusercontent.com/17263249/208312362-e3605c66-c0d8-4e3b-8f0c-5d97883cc70e.png)

The fifth step is to configure the GroundMask that represents the "Terrain/Floor" of your Scene:

![image](https://user-images.githubusercontent.com/17263249/208312514-6dd3f9c1-acfd-4fea-92c1-d9073f3a270c.png)

The sixth step is to add the NavmeshAgent and the CharacterController to your GameObject representing the PlayerController.

![image](https://user-images.githubusercontent.com/17263249/208312482-8a788ee8-3010-4d0a-8017-803d893d969e.png)

![image](https://user-images.githubusercontent.com/17263249/208312489-c100edff-cd54-46d1-b816-2a7d16a3a662.png)

And finally, you can configure the other variables according to your needs, each variable has a brief description in the C# code.

<h2>Documentacão em Portugues</h2>

<b>Qualquer sugestão ou problema encontrado, voce pdoe abrir uma Issue no github de documentacão do projeto: https://github.com/MUN1Z/Classic-MMORPG-Camera-And-Controller</b>

<h3>Configuracão do CameraController</h3>

O primeiro passo é criar um GameObject para representar o CameraController:

![image](https://user-images.githubusercontent.com/17263249/208306028-b068a70e-6c44-4bc8-a25e-9024fc2ea0c4.png)

O segundo passo é criar um GameObject para representar o Parent da Main Camera:

![image](https://user-images.githubusercontent.com/17263249/208306123-47d0594a-48b5-41f9-b64e-d8b0c41d048a.png)

O terceiro passo é colocar a Main Camera dentro do Parent Camera:

![image](https://user-images.githubusercontent.com/17263249/208306135-d8f593d5-33ec-4f5b-b3ed-9a78fb3f8d8d.png)

O quarto passo é colocar o script CameraController.cs no seu GameObject que representa o CameraController:

![image](https://user-images.githubusercontent.com/17263249/208306248-eb3d821d-446f-4a1e-b0e2-bad383d18567.png)

![image](https://user-images.githubusercontent.com/17263249/208306182-73e98446-0645-4d65-aad1-e3a8e6d5b4fc.png)

O quinto passo é colocar o GameObject que representa o Parent da Camera na variavel no Field "Camera Parent" do CameraController.cs:

![image](https://user-images.githubusercontent.com/17263249/208306404-8a25e0d3-9f2a-4f3b-9f16-fe7226ae3031.png)

O sexto passo é configurar o CollisionMask que representa o "Terreno/Piso" da sua Scene:

![image](https://user-images.githubusercontent.com/17263249/208306612-ad8ad54b-5765-443f-b354-36509ee876f4.png)

E por fim voce pode configurar as outras variaveis de acordo com a sua necessidade, cada váriavél possui uma breve descricão no código C#.

<h3>Configuracão do PlayerController</h3>

O primeiro passo é criar um GameObject para representar o PlayerController:

![image](https://user-images.githubusercontent.com/17263249/208312133-8734dfed-7861-4c14-82fa-834bfe6157ca.png)

O segundo passo é criar um GameObject para representar a direcão do player, dentro do PlayerController:

![image](https://user-images.githubusercontent.com/17263249/208312319-c48f63fa-ba67-469f-aef9-2977ae768f45.png)

O terceiro passo é colocar o script PlayerController.cs no seu GameObject que representa o PlayerController:

![image](https://user-images.githubusercontent.com/17263249/208312242-4a689b0b-d785-4c66-8138-4d339c24c70a.png)

![image](https://user-images.githubusercontent.com/17263249/208312331-3ba64553-9bf0-44cc-ae26-d6a8783c18f3.png)

O quarto passo é colocar o GameObject que representa a Direcão, na variavel "Direction" do PlayerController:

![image](https://user-images.githubusercontent.com/17263249/208312362-e3605c66-c0d8-4e3b-8f0c-5d97883cc70e.png)

O quinto passo é configurar o GroundMask que representa o "Terreno/Piso" da sua Scene:

![image](https://user-images.githubusercontent.com/17263249/208312514-6dd3f9c1-acfd-4fea-92c1-d9073f3a270c.png)

O sexto passo é adicionar o NavmeshAgent e o CharacterController ao seu GameObject que representa o PlayerController.

![image](https://user-images.githubusercontent.com/17263249/208312482-8a788ee8-3010-4d0a-8017-803d893d969e.png)

![image](https://user-images.githubusercontent.com/17263249/208312489-c100edff-cd54-46d1-b816-2a7d16a3a662.png)

E por fim voce pode configurar as outras variaveis de acordo com a sua necessidade, cada váriavél possui uma breve descricão no código C#.
