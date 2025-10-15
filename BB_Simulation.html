from IPython.display import HTML

HTML("""
<!DOCTYPE html>
<html>
<head>
  <meta charset="utf-8">
  <title>3D Big Bang Simulation with Colorful Spheres</title>
  <style>
    body { margin: 0; overflow: hidden; background: black; }
    canvas { width: 100%; height: 100% }
  </style>
</head>
<body>
<script src="https://cdn.jsdelivr.net/npm/three@0.128.0/build/three.min.js"></script>
<script>

const scene = new THREE.Scene();
scene.background = new THREE.Color(0x000000);

const camera = new THREE.PerspectiveCamera(
  75, window.innerWidth/window.innerHeight, 0.1, 1000
);
camera.position.z = 20;

const renderer = new THREE.WebGLRenderer({ antialias: true });
renderer.setSize(window.innerWidth, window.innerHeight);
document.body.appendChild(renderer.domElement);


const particleCount = 300;
const spheres = [];
const velocities = [];

for (let i = 0; i < particleCount; i++) {
  const geometry = new THREE.SphereGeometry(0.2, 8, 8);
  const color = new THREE.Color(`hsl(${Math.random() * 360}, 100%, 60%)`);
  const material = new THREE.MeshBasicMaterial({ color: color });
  const sphere = new THREE.Mesh(geometry, material);

  
  sphere.position.set(0, 0, 0);
  scene.add(sphere);
  spheres.push(sphere);

 
  const theta = Math.random() * 2 * Math.PI;
  const phi = Math.acos(2 * Math.random() - 1);
  const speed = 0.001 + Math.random() * 1;

  const vx = speed * Math.sin(phi) * Math.cos(theta);
  const vy = speed * Math.sin(phi) * Math.sin(theta);
  const vz = speed * Math.cos(phi);

  velocities.push(new THREE.Vector3(vx, vy, vz));
}


function animate() {
  requestAnimationFrame(animate);

  for (let i = 0; i < particleCount; i++) {
    spheres[i].position.add(velocities[i]);
  }

  scene.rotation.y += 0.002;
  renderer.render(scene, camera);
}

animate();


window.addEventListener('resize', () => {
  camera.aspect = window.innerWidth / window.innerHeight;
  camera.updateProjectionMatrix();
  renderer.setSize(window.innerWidth, window.innerHeight);
});
</script>
</body>
</html>
""")
