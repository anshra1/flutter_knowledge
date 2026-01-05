# Native Widgets index

A collection of built-in Flutter widgets that solve specific layout and architectural challenges.

---

## 1. [Layout Builder](./layout_builder.md)
*   **Purpose:** Responds to parent constraints to make structural layout decisions.
*   **Key Use Case:** Adaptive UI (Row to Column switches).

## 2. [Baseline](./baseline.md)
*   **Purpose:** Aligns text/icons using typographic baselines instead of bounding boxes.
*   **Key Use Case:** Mixed font sizes and mathematical notations.

## 3. [Offstage](./offstage.md)
*   **Purpose:** Keeps widgets alive in the tree while hiding them from layout and paint.
*   **Key Use Case:** Preserving state in hidden tabs or forms.

## 4. [DecoratedBox](./decorated_box.md)
*   **Purpose:** A lightweight way to apply `BoxDecoration` without `Container` overhead.
*   **Key Use Case:** Purely visual styling (borders, backgrounds).

## 5. [PhysicalModel](./physical_model.md)
*   **Purpose:** Realistic elevation and shadow calculation with integrated clipping.
*   **Key Use Case:** Custom Material-style surfaces and elevated cards.