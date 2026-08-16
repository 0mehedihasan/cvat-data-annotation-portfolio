# Keypoints & Skeleton Annotation

## Task Information

| Field | Details |
|---|---|
| Annotation Tool | CVAT |
| Annotation Type | Keypoints & Skeleton |
| Shape Type | Skeleton |
| Task Type | Human Pose Annotation |
| Input Type | Image Sequence |
| Annotation Mode | Manual |
| Number of Skeletons | 2 |
| Number of Keypoints | 15 per skeleton |
| Total Keypoints | 30 |
| Number of Frames | 2 |
| Start Frame | 0 |
| Stop Frame | 1 |
| Interpolation | Not used |
| Status | Completed |

## Objective

The objective of this practical task was to annotate human body keypoints and construct a skeleton representation using CVAT.

The task demonstrates how anatomical landmarks can be represented as keypoints and connected to describe human body structure and pose.

## Skeleton Label

| Label | Description |
|---|---|
| sklenton | Human body skeleton composed of connected anatomical keypoints |

## Keypoints

The skeleton contains 15 keypoints:

| Keypoint | Description |
|---|---|
| head | Head position |
| neck | Neck position |
| L_Shoulder | Left shoulder |
| R_Shoulder | Right shoulder |
| L_Elbow | Left elbow |
| R_Elbow | Right elbow |
| L_Hand | Left hand |
| R_Hand | Right hand |
| Mid_hip | Center of the hip |
| L_Hip | Left hip |
| R_Hip | Right hip |
| L_Knee | Left knee |
| R_Knee | Right knee |
| L_foot | Left foot |
| R_foot | Right foot |

## Annotation Statistics

The completed CVAT task contains **2 manually annotated skeletons** across **2 frames**.

| Annotation Type | Count |
|---|---:|
| Rectangle | 0 |
| Polygon | 0 |
| Polyline | 0 |
| Points | 30 |
| Ellipse | 0 |
| Cuboid | 0 |
| Skeleton | 2 |
| Mask | 0 |
| Tag | 0 |

### Summary

- **Skeletons:** 2
- **Keypoints:** 30
- **Keypoints per skeleton:** 15
- **Frames:** 2
- **Manually annotated skeletons:** 2
- **Interpolated skeletons:** 0

## Annotation Process

1. Created the annotation task in CVAT.
2. Created the `sklenton` skeleton label.
3. Defined the required body keypoints.
4. Loaded the human pose image sequence.
5. Placed keypoints on the corresponding body locations.
6. Connected the keypoints to form the human skeleton.
7. Annotated the skeleton across the available frames.
8. Reviewed the keypoint positions and connections.
9. Verified the completed annotations.
10. Saved the annotation task.

## Annotation Rules

The following principles were applied:

- Each anatomical landmark was assigned to the appropriate keypoint.
- Keypoints were positioned on the corresponding body locations.
- Left and right body parts were distinguished.
- The skeleton connections were maintained consistently.
- The same keypoint structure was used across frames.
- All skeleton annotations were manually created.
- No interpolation was used.

## Before Annotation

The original image before keypoint and skeleton annotation.

![Before Annotation](screenshots/before.png)

## After Annotation

The completed CVAT skeleton annotation showing the keypoints and connections.

![After Annotation](screenshots/after.png)

## Quality Considerations

The completed skeleton annotations were reviewed based on:

- Correct anatomical landmark identification
- Correct left and right keypoint assignment
- Accurate keypoint placement
- Consistent skeleton structure
- Correct keypoint connections
- Consistency across frames
- Verification of the final annotation count

## Skills Demonstrated

- CVAT skeleton annotation
- Human pose annotation
- Keypoint localization
- Anatomical landmark identification
- Multi-frame annotation
- Skeleton construction
- Manual annotation
- Annotation quality control

## Practical Outcome

This practical task demonstrates the use of CVAT for human pose annotation using keypoints and skeleton structures.

A total of **2 skeletons** were manually annotated across **2 frames**, containing **30 keypoints in total**.

Each skeleton consisted of **15 anatomical keypoints** representing the head, neck, shoulders, elbows, hands, hips, knees, and feet.

## Annotation File

The `annotation.xml` file contains the structured CVAT annotation output for this practical task.

It preserves the machine-readable annotation information associated with the skeletons, keypoints, frame data, and labels.

## Evidence and Files

```text
keypoints-skeleton/
├── keypoints-skeleton.md
├── annotation.xml
└── screenshots/
    ├── before.png
    └── after.png