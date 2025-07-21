# SAM-Zero3D: Zero-Shot 3D Scene Segmentation Using SAM

SAM-Zero3D is a training-free framework that extends the Segment Anything Model (SAM) to 3D scene segmentation. By transferring multi-view 2D masks into 3D space, it enables accurate semantic segmentation without the need for 3D annotations or training.

## Key Features:
- **Global Anchor Point-guided Branch**: Projects 3D anchor points across multiple views, creating a robust cross-view mask alignment for consistent 3D label assignment.
- **Local Geometry-driven Branch**: Partitions point clouds into regions, estimates semantic similarity, and merges similar regions using a multi-stage strategy.
- **Iterative Global–Local Interaction**: Combines global semantic priors with local geometric details for enhanced segmentation accuracy.

## Results  
SAM-Zero3D outperforms existing zero-shot methods, achieving accurate segmentation on ShapeNetPart, ScanNetV2, and ScanNet200.

## Code  
The code will be available soon.
