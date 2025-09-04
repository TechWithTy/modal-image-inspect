# Modal Image Inspect Component

This module provides components for inspecting images in a modal view with zoom and navigation capabilities.

## Files

- [ModalImageLens.tsx](cci:7://file:///c:/Users/tyriq.DESKTOP-U7P592K/OneDrive/Documents/Github-New/deal-scale-app/external/modal-image-inspect/ModalImageLens.tsx:0:0-0:0): Main component for image inspection with zoom/pan functionality
- [index.ts](cci:7://file:///c:/Users/tyriq.DESKTOP-U7P592K/OneDrive/Documents/Github-New/deal-scale-app/external/drawer-flow/index.ts:0:0-0:0): Module exports

## Features
- Zoomable image inspection
- Modal overlay display
- Navigation controls
- Responsive design

## Usage
```typescript
import { ModalImageLens } from '@/external/modal-image-inspect';

function Example() {
  const [isOpen, setIsOpen] = useState(false);
  
  return (
    <ModalImageLens 
      src="/path/to/image.jpg" 
      alt="Description" 
      isOpen={isOpen} 
      onClose={() => setIsOpen(false)} 
    />
  );
}