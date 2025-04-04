
<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, user-scalable=no, minimum-scale=1.0, maximum-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>My first AR app</title>
    <script src="https://aframe.io/releases/1.2.0/aframe.min.js"></script>
    <script src="https://raw.githack.com/AR-js-org/AR.js/master/aframe/build/aframe-ar.js"></script>                      
</head>
<body>    
    <a-scene embedded arjs>
        <a-marker preset="hiro">
            <a-entity
                position="0 0 0"
                scale="0.5 0.5 0.5"
                gltf-model="https://cdn.rawgit.com/KhronosGroup/glTF-Sample-Models/master/2.0/DamagedHelmet/glTF/DamagedHelmet.gltf"
            ></a-entity>
        </a-marker>
        <a-entity camera></a-entity>
    </a-scene>
</body>
</html>

                                            
