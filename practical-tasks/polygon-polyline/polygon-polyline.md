# Polygon and Polyline Annotation

## Task Information

| Field             | Details                       |
| ----------------- | ----------------------------- |
| Annotation Tool   | CVAT                          |
| Annotation Type   | Polygon                       |
| Shape Type        | Polygon                       |
| Task Type         | Shape-Based Object Annotation |
| Input Type        | Image                         |
| Annotation Mode   | Manual                        |
| Number of Classes | 2                             |
| Total Annotations | 5                             |
| Number of Frames  | 1                             |
| Start Frame       | 0                             |
| Stop Frame        | 0                             |
| Interpolation     | Not used                      |
| Status            | Completed                     |

## Objective

The objective of this practical task was to practice polygon-based annotation in CVAT by accurately outlining objects with different geometric shapes.

Two classes were created:

* `circle`
* `square`

A total of five polygon annotations were manually created.

## Classes / Labels

| Class  | Description                                              |
| ------ | -------------------------------------------------------- |
| circle | Circular objects annotated using polygon boundaries      |
| square | Square-shaped objects annotated using polygon boundaries |

## Annotation Statistics

The completed CVAT task contains **5 manually annotated polygons**.

| Class     | Polygon Annotations | Manually Annotated | Interpolated | Total |
| --------- | ------------------: | -----------------: | -----------: | ----: |
| circle    |                   2 |                  2 |            0 |     2 |
| square    |                   3 |                  3 |            0 |     3 |
| **Total** |               **5** |              **5** |        **0** | **5** |

### Annotation Distribution

* **circle:** 2
* **square:** 3
* **Total:** 5

## Annotation Process

1. Created the annotation task in CVAT.
2. Defined two classes: `circle` and `square`.
3. Selected the Polygon annotation tool.
4. Identified the target shapes in the image.
5. Created polygon boundaries around the target objects.
6. Assigned the appropriate class label.
7. Repeated the process for all five target objects.
8. Reviewed the completed annotations.
9. Verified the class assignments and polygon boundaries.
10. Saved the completed annotation task.

## Annotation Rules

The following principles were applied:

* Each target shape was assigned the appropriate class.
* Each individual object was annotated separately.
* Polygon points were placed along the visible boundary of each object.
* The appropriate class label was assigned to each polygon.
* All annotations were manually created.
* No interpolation was used.
* The completed annotations were reviewed before finalizing the task.

## Before Annotation

The original image before annotation.

![Before Annotation](screenshots/before.png)

## After Annotation

The completed CVAT annotation showing the manually created polygon boundaries.

![After Annotation](screenshots/after.png)

## CVAT Annotation Statistics

| Annotation Type | Count |
| --------------- | ----: |
| Rectangle       |     0 |
| Polygon         |     5 |
| Polyline        |     0 |
| Points          |     0 |
| Ellipse         |     0 |
| Cuboid          |     0 |
| Skeleton        |     0 |
| Mask            |     0 |
| Tag             |     0 |

All **5 annotations were manually created**, with **0 interpolated annotations**.

## Quality Considerations

The completed annotations were reviewed based on:

* Correct object identification
* Correct class assignment
* Accurate polygon placement
* Appropriate coverage of the target objects
* Consistent annotation methodology
* Correct number of polygon vertices
* Verification of the final annotation count

## Skills Demonstrated

* CVAT task creation
* Polygon annotation
* Shape-based object annotation
* Multi-class labeling
* Object boundary definition
* Manual annotation
* Class assignment
* Annotation review
* Dataset quality checking

## Practical Outcome

This practical task demonstrates the use of polygon annotation for defining object boundaries in an image.

A total of **5 object instances** were manually annotated across two classes:

**2 circles and 3 squares.**

The task demonstrates how polygon annotations can provide more flexible object boundaries than rectangular bounding boxes when the shape or boundary of an object needs to be represented more precisely.

## Evidence

The `screenshots/` directory contains the visual evidence for this practical task:

```text
polygon-polyline/
├── polygon-polyline.md
└── screenshots/
    ├── before.png
    └── after.png
```

`before.png` contains the original unannotated image.

`after.png` contains the completed CVAT polygon annotations.

## Reference

[CVAT Academy: Polygons & Polylines in CVAT](https://www.cvat.ai/academy/polygon-and-polyline-annotation)
