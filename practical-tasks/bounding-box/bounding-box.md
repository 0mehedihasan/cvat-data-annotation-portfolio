# Bounding Box Annotation

## Task Information

| Field             | Details          |
| ----------------- | ---------------- |
| Annotation Tool   | CVAT             |
| Annotation Type   | Bounding Box     |
| Shape Type        | Rectangle        |
| Task Type         | Object Detection |
| Input Type        | Image            |
| Annotation Mode   | Manual           |
| Number of Classes | 4                |
| Total Annotations | 28               |
| Number of Frames  | 1                |
| Start Frame       | 0                |
| Stop Frame        | 0                |
| Interpolation     | Not used         |
| Status            | Completed        |

## Objective

The objective of this practical task was to identify and localize objects in a real-world street scene using rectangular bounding boxes in CVAT.

Four object categories were annotated:

* Person
* Car
* Bicycle
* MotorCycle

Each object instance was manually localized using a rectangular bounding box and assigned to its corresponding class.

## Classes / Labels

| Class      | Description                                |
| ---------- | ------------------------------------------ |
| Person     | Visible people or pedestrians in the scene |
| Car        | Cars visible in the scene                  |
| Bicycle    | Bicycle visible in the scene               |
| MotorCycle | Motorcycle visible in the scene            |

## Annotation Statistics

The completed CVAT task contains **28 manually annotated rectangular objects**.

| Class      | Rectangle Annotations | Manually Annotated | Interpolated |  Total |
| ---------- | --------------------: | -----------------: | -----------: | -----: |
| Person     |                    24 |                 24 |            0 |     24 |
| Car        |                     2 |                  2 |            0 |      2 |
| Bicycle    |                     1 |                  1 |            0 |      1 |
| MotorCycle |                     1 |                  1 |            0 |      1 |
| **Total**  |                **28** |             **28** |        **0** | **28** |

### Annotation Distribution

* **Person:** 24
* **Car:** 2
* **Bicycle:** 1
* **MotorCycle:** 1
* **Total:** 28

## Annotation Process

1. Created the annotation task in CVAT.
2. Defined four object classes.
3. Selected the Rectangle annotation tool.
4. Identified the target objects in the image.
5. Created a bounding box around each target object.
6. Assigned the appropriate class label.
7. Repeated the process for all target objects.
8. Reviewed the completed annotations.
9. Verified the class assignments and bounding box placement.
10. Saved the completed annotation task.

## Annotation Rules

The following principles were applied:

* Each target object was assigned the appropriate class.
* Each individual object was annotated separately.
* Bounding boxes were drawn around the visible target objects.
* Bounding boxes were positioned as accurately as possible.
* The appropriate class label was assigned to each rectangle.
* All annotations were manually created.
* No interpolation was used.
* The completed annotations were reviewed before finalizing the task.

## Before Annotation

The original image before annotation.

![Before Annotation](screenshots/before.png)

## After Annotation

The completed CVAT annotation showing the manually created bounding boxes.

![After Annotation](screenshots/after.png)

## CVAT Annotation Statistics

| Annotation Type | Count |
| --------------- | ----: |
| Rectangle       |    28 |
| Polygon         |     0 |
| Polyline        |     0 |
| Points          |     0 |
| Ellipse         |     0 |
| Cuboid          |     0 |
| Skeleton        |     0 |
| Mask            |     0 |
| Tag             |     0 |

All **28 annotations were manually created**, with **0 interpolated annotations**.

## Quality Considerations

The completed annotations were reviewed based on:

* Correct object identification
* Correct class assignment
* Appropriate bounding box placement
* Coverage of the visible target object
* Minimization of unnecessary background
* Consistent annotation of individual object instances
* Verification of the final annotation count

## Skills Demonstrated

* CVAT task creation
* Bounding box annotation
* Rectangle annotation
* Multi-class object detection labeling
* Object localization
* Manual annotation
* Class assignment
* Annotation review
* Dataset quality checking

## Practical Outcome

This practical task demonstrates the conversion of an unannotated street scene into a structured object detection annotation.

A total of **28 object instances** were manually annotated across four classes:

**24 Persons, 2 Cars, 1 Bicycle, and 1 MotorCycle.**

The resulting annotations provide structured object localization information for a computer vision object detection workflow.

## Annotation File

The `annotation.xml` file contains the structured CVAT annotation output for this practical task.

It preserves machine-readable annotation information, including:

* Annotation labels
* Bounding box coordinates
* Object instances
* Frame information
* Annotation metadata

## Evidence and Files

The complete practical task contains:

```text
bounding-box/
├── bounding-box.md
├── annotation.xml
└── screenshots/
    ├── before.png
    └── after.png
```

`before.png` contains the original unannotated image.

`after.png` contains the completed CVAT annotation.

`annotation.xml` contains the structured annotation data exported from CVAT.

## Reference

[CVAT Academy: Bounding Box Annotation](https://www.cvat.ai/academy/bounding-box-annotation)
