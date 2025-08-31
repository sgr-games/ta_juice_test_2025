# Reward Popup System - Unity Implementation

## Task Overview
Technical Art implementation of a reward popup system based on the provided PSD design 
- [reward_popup.psd](reward_popup.psd)
- [bossChestOpen.psb](bossChestOpen.psb)
- [ItemsRawArt](ItemsRawArt)

![img.png](img.png)
## Requirements

### Design Implementation
- [ ] Implement the reward popup UI from [reward_popup.psd](reward_popup.psd)
- [ ] Create sprite sheets for all UI elements
- [ ] Maintain visual fidelity to the original design

### Animation States
The popup should support 3 distinct animation states:

1. **Open Chest and Winning**
   - Chest opening animation
   - Reward reveal with celebratory effects
   - Smooth transition into idle state

2. **Idle** 
   - Subtle breathing/floating animation
   - Particle effects or glow to maintain engagement
   - Ready state for user interaction

3. **Closing Popup**
   - Smooth exit animation
   - Clean transition out of view
   - Reset state for next use

### Technical Requirements
- [ ] **Sprite Sheets**: All sprites organized in optimized sprite sheets
- [ ] **VFX Integration**: Include visual effects for enhanced user experience, particles, shaders, etc.
- [ ] **Modular Design**: Easy to modify and extend for future popup variations
- [ ] **Performance Optimized**: Efficient rendering and animation systems

### Deliverables
- [ ] Complete Unity prefab ready for integration
- [ ] Sprite sheets with proper import settings
- [ ] Animation controllers for all 3 states
- [ ] VFX systems (particles, shaders, etc.)
- [ ] Documentation for customization
- [ ] Example integration script

## Future Considerations
The system should be designed with scalability in mind:
- Easy to create new popup variants
- Configurable rewards and content
- Reusable animation patterns
- Consistent UI framework integration

## Notes
- Ensure all assets are properly organized in the project structure
- Follow Unity best practices for UI and animation
- Test on multiple screen resolutions
- Consider performance on target platforms