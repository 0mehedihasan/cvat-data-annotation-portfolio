# Cuboid Annotation

## Task Information

| Field | Details |
|---|---|
| Annotation Tool | CVAT |
| Annotation Type | Cuboid |
| Shape Type | 3D Cuboid |
| Task Type | 3D Object Annotation |
| Input Type | Image Sequence |
| Annotation Mode | Manual |
| Number of Classes | 1 |
| Total Annotations | 2 |
| Number of Frames | 2 |
| Start Frame | 0 |
| Stop Frame | 1 |
| Interpolation | Not used |
| Status | Completed |

## Objective

The objective of this practical task was to annotate vehicles using 3D cuboids in CVAT.

The task demonstrates how cuboid annotations can represent the approximate three-dimensional extent of an object from a two-dimensional image.

## Class / Label

| Class | Description |
|---|---|
| Car | Vehicle annotated using a 3D cuboid |

## Annotation Statistics

The completed CVAT task contains **2 manually annotated cuboids**.

| Class | Cuboid Annotations | Manually Annotated | Interpolated | Total |
|---|---:|---:|---:|---:|
| Car | 2 | 2 | 0 | 2 |
| **Total** | **2** | **2** | **0** | **2** |

### Annotation Distribution

- **Car:** 2 cuboids
- **Total:** 2 cuboids

## Annotation Process

1. Created the annotation task in CVAT.
2. Added the `Car` class.
3. Loaded the car image sequence.
4. Selected the Cuboid annotation tool.
5. Created a 3D cuboid around the visible vehicle.
6. Adjusted the cuboid dimensions to represent the vehicle's approximate 3D structure.
7. Annotated the vehicle across the available frames.
8. Reviewed the cuboid placement.
9. Verified the completed annotations.
10. Saved the annotation task.

## Annotation Rules

The following principles were applied:

- Each vehicle was assigned to the `Car` class.
- The cuboid was positioned around the visible vehicle.
- The cuboid was adjusted according to the object's perspective.
- The approximate front, rear, sides, top, and bottom of the vehicle were represented.
- All annotations were manually created.
- No interpolation was used.
- The completed annotations were reviewed before finalizing the task.

## Before Annotation

The original image before annotation.

![Before Annotation](screenshots/before.png)

## After Annotation

The completed CVAT cuboid annotations.

![After Annotation](screenshots/after.png)

## CVAT Annotation Statistics

| Annotation Type | Count |
|---|---:|
| Rectangle | 0 |
| Polygon | 0 |
| Polyline | 0 |
| Points | 0 |
| Ellipse | 0 |
| Cuboid | 2 |
| Skeleton | 0 |
| Mask | 0 |
| Tag | 0 |

All **2 annotations were manually created**, with **0 interpolated annotations**.

## Quality Considerations

The completed annotations were reviewed based on:

- Correct vehicle identification
- Correct class assignment
- Appropriate cuboid placement
- Alignment with the visible vehicle
- Consistency across frames
- Appropriate representation of the object's 3D extent
- Verification of the final annotation count

## Skills Demonstrated

- CVAT cuboid annotation
- 3D object annotation
- Vehicle localization
- Perspective-based annotation
- Multi-frame annotation
- Manual annotation
- Annotation quality control
- Dataset preparation

## Practical Outcome

This practical task demonstrates the use of CVAT's Cuboid tool for representing the approximate three-dimensional extent of vehicles in image sequences.

A total of **2 Car cuboids** were manually annotated across **2 frames**.

## Annotation File

The `annotation.xml` file contains the structured CVAT annotation output for this practical task.

It preserves the machine-readable annotation information associated with the cuboid annotations, labels, and frame data.

## Evidence and Files

```text
cuboids/
├── cuboids.md
├── annotation.xml
└── screenshots/
    ├── before.png
    └── after.png