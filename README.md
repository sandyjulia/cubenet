# sandyjulia.github.io
Hier sehen sie einen Würfel und die Animation des zugehörigen Würfelnetzes. Dafür werden kanji- und hiro-Marker benötigt.
Here you can see a cube and the belonging animation of a cubenet. For this you´ll need a kanji- and hiro-marker.
<!DOCTYPE html>
<html>
  <head>
    <script src="https://aframe.io/releases/1.1.0/aframe.min.js"></script>
    <script src="https://jeromeetienne.github.io/AR.js/aframe/build/aframe-ar.js">
    </script>
      </head>
  <body>
    <a-scene embedded arjs>
      <a-marker preset="hiro">
      <a-plane position="0 0 0" color="blue" height="1" width="1" rotation="-90 0 0" opacity="0.8"> 
        <a-entity>
          <a-plane position="0.5 0 0.5" color="pink" height="1" width="1" rotation="0 -90 0" opacity="0.8"
               animation__2="property: position; to: 1 0 0; dur: 15000; easing: linear; loop: true"
               animation__3="property: rotation; to: 0 0 0; dur: 15000; easing: linear; loop: true"></a-plane>
          <a-plane position="0.5 0 0.5" color="pink" height="1" width="1" rotation="0 90 0" opacity="0.8"
               animation__2="property: position; to: 1 0 0; dur: 15000; easing: linear; loop: true"
               animation__3="property: rotation; to: 0 180 0; dur: 15000; easing: linear; loop: true"></a-plane>
            <a-plane position="-0.5 0 0.5" color= "red" height="1" width="1" rotation="0 90 0" opacity="0.8"
                     animation="property: position; to: -1 0 0; dur: 15000; easing: linear; loop: true"
                     animation__2="property: rotation; to: 0 0 0; dur: 15000; easing: linear; loop: true"></a-plane>
          <a-plane position="-0.5 0 0.5" color= "red" height="1" width="1" rotation="0 -90 0" opacity="0.8"
                     animation="property: position; to: -1 0 0; dur: 15000; easing: linear; loop: true"
                     animation__2="property: rotation; to: 0 -180 0; dur: 15000; easing: linear; loop: true"></a-plane>
           <a-entity animation= "property:position; to:0 0 0; dur: 10000; easing: linear; loop:true">
           <a-plane position="0 0 1" color= "purple" height="1" width="1" rotation="0 0 0" opacity="0.8"
                    animation__2="property: position; to: -2 0 0; dur: 15000; easing: linear; loop: true"
                    animation="property: rotation; to: 0 -180 0; dur: 15000; easing: linear; loop: true"></a-plane>
             <a-plane position="0 0 1" color= "purple" height="1" width="1" rotation="0 180 0" opacity="0.8"
                    animation__2="property: position; to: -2 0 0; dur: 15000; easing: linear; loop: true"
                    animation="property: rotation; to: 0 0 0; dur: 15000; easing: linear; loop: true"></a-plane>
          </a-entity>
          <a-plane position="0 0.5 0.5" color= "yellow" height="1" width="1" rotation="90 0 0" opacity="0.8"
                   animation="property: position; to: 0 1 0; dur: 15000; easing: linear; loop: true"
                     animation__2="property: rotation; to: 0 0 0; dur: 15000; easing: linear; loop: true"></a-plane>
          <a-plane position="0 0.5 0.5" color= "yellow" height="1" width="1" rotation="-90 0 0" opacity="0.8"
                   animation="property: position; to: 0 1 0; dur: 15000; easing: linear; loop: true"
                     animation__2="property: rotation; to: -180 0 0; dur: 15000; easing: linear; loop: true"></a-plane>
          <a-plane position="0 -0.5 0.5" color= "green" height="1" width="1" rotation="-90 0 0" opacity="0.8"
                   animation="property: position; to: 0 -1 0; dur: 15000; easing: linear; loop: true"
                     animation__2="property: rotation; to: 0 0 0; dur: 15000; easing: linear; loop: true"></a-plane>
          <a-plane position="0 -0.5 0.5" color= "green" height="1" width="1" rotation="90 0 0" opacity="0.8"
                   animation="property: position; to: 0 -1 0; dur: 15000; easing: linear; loop: true"
                     animation__2="property: rotation; to: 180 0 0; dur: 15000; easing: linear; loop: true"></a-plane>
        </a-entity>
      </a-plane>
      </a-marker>
      <a-marker preset="kanji">
      <a-plane position="0 0 0" color="blue" height="1" width="1" rotation="-90 0 0" opacity="0.8"> 
        <a-entity>
          <a-plane position="0.5 0 0.5" color="pink" height="1" width="1" rotation="0 -90 0" opacity="0.8"></a-plane>
          <a-plane position="0.5 0 0.5" color= "pink" height= "1" width="1" rotation="0 90 0" opacity="0.8"></a-plane>
            <a-plane position="-0.5 0 0.5" color= "red" height="1" width="1" rotation="0 -90 0" opacity="0.7"></a-plane>
          <a-plane position="-0.5 0 0.5" color= "red" height="1" width="1" rotation="0 90 0" opacity="1"></a-plane>
           <a-plane position="0 0 1" color= "purple" height="1" width="1" rotation="0 0 0" opacity="0.7"></a-plane>
          <a-plane position="0 0 1" color= "purple" height="1" width="1" rotation="180 0 0" opacity="0.8"></a-plane>
          <a-plane position="0 0.5 0.5" color= "yellow" height="1" width="1" rotation="90 0 0" opacity="1"></a-plane>
          <a-plane position="0 0.5 0.5" color= "yellow" height="1" width="1" rotation="-90 0 0" opacity="0.8"></a-plane>
          <a-plane position="0 -0.5 0.5" color= "green" height="1" width="1" rotation="90 0 0" opacity="0.8"></a-plane>
          <a-plane position="0 -0.5 0.5" color= "green" height="1" width="1" rotation="-90 0 0" opacity="1"></a-plane>
        </a-entity>
      </a-plane>
      </a-marker>
      <a-camera position="0 0 0"> </a-camera>
    </a-scene>
  </body>
</html>
