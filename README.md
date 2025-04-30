# SAMUEL EMMANUEL KIMARO
# OOP_ASSIGNMENT_PLP
## Assignment 1: Design Your Own Class! 🏗️

## Overview
This repository contains Python-based solutions to a programming assignment that explores object-oriented programming concepts such as classes, inheritance, and polymorphism.

### Key Activities:
1. **Design Your Own Class**:
    - Create a class of your choice (`Device`), representing real-world objects.
    - Add attributes and methods to define functionality.
    - Implement inheritance with a derived class (`Smartphone`) for specific features.
    - Explore encapsulation and polymorphism through method overrides.

2. **Polymorphism Challenge**:
    - Create classes for different objects (e.g., `Car`, `Plane`, `Bicycle`) inheriting from a base class (`Vehicle`).
    - Each class defines a common method (`move`) with its unique behavior.

---

## Project Structure
### Files:
- `class_definition.py`: Contains class implementations and methods for Assignment 1.

---

### Example Classes:
#### `Device` (Base Class):
- Attributes: `brand`, `model`
- Methods: `power_on`, `power_off`

#### `Smartphone` (Derived Class):
- Attributes: `brand`, `model`, `battery_level`
- Methods: `check_battery`, `charge_phone`, `make_call`

#### Polymorphism:
- **Base Class**: `Vehicle`
- **Derived Classes**: `Car`, `Plane`, `Bicycle`
- **Unique Actions**:
  - `Car.move()`: Driving 🚗
  - `Plane.move()`: Flying ✈️
  - `Bicycle.move()`: Pedaling 🚴

---

## Example Usage
### Activity 1: Class and Inheritance

```python
my_phone = Smartphone("Apple", "iPhone 16 Pro Max", 85)
my_phone.power_on()
my_phone.check_battery()
my_phone.make_call("+254713442011")
my_phone.charge_phone()
my_phone.check_battery()


vehicle1 = Car()
vehicle2 = Plane()
vehicle3 = Bicycle()

vehicle1.move()  # Output: Driving
vehicle2.move()  # Output: Flying
vehicle3.move()  # Output: Pedaling




