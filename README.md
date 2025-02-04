# A Modpack Based on 1.12.2 and Relictium

## Why Create This Pack?

### Designed for mobile FCL launcher to address poor efficiency of legacy OptiFine on mobile devices:
- **Performance Issues**: 
  - 70 FPS average in regular maps (2 render distance)  
  - ~100 FPS in skyblock maps

### Core Components:
- **Relictium**: Sodium port for 1.12.2 (10-15x FPS boost)  
- **Visual Enhancements**:  
  - Interface background blur (mimicking modern version UIs)  
  - NeverEnoughAnimation (enhanced item animations)  
  - Aqua Acrobatics (modern swimming mechanics)  
- **QoL Improvements**:  
  - Modern splash screen (desktop exclusive)  
  - Smooth Font mod  
  - Universal Tweaks compatibility layer

## Optimization Results (12 chunks | Max settings)

| Hardware Configuration          | Peak FPS (Sky View) | Minimum FPS (Chunk Loading) |
|----------------------------------|---------------------|-----------------------------|
| E5-2666v3 + GTX 1660S @ 1080p   | 870                 | 400                         |
| Dimensity 9200+ (Redmi K60 Ultra)| 500                 | 110                         |

## Compatibility Guide
### ✔️ Windows: Full support
### 📱 Android: 
- Required renderers:  
  - **Holy Renderer** (recommended)  
  - Krypton Wrapper Renderer (experimental, known issues)  
- Critical notice: Disable *Smooth Font* mod

## Shader Support Status
❌ **Oculus 1.12.2 Port**:  
- Development halted (last commit 6 months ago)  
- 3 failed GitHub Actions builds  
- Shaders currently unsupported

## License & Contribution
This pack is licensed under **MIT**. You may:  
- Create derivative modpacks  
- Redistribute with attribution  
- Report issues via:  
  - Comment section  
  - [DHJComical@gmail.com](mailto:DHJComical@gmail.com)  
