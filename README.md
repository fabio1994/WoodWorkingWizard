![Python Version](https://img.shields.io/badge/python-3.11-blue)
![License ](https://img.shields.io/badge/License-GPL_3.0-green)
![Release](https://img.shields.io/badge/Release-V2.1.3-green)


# WoodWorkingWizard
Wood Working Wizard Plugin for Fusion 360.

## 🚀 What's New in Version 2.1.1

### **Major Feature Enhancements**

#### **Revolutionary Drawer System**
- **Custom Drawer Depths**: Override default depth with user-specified values, validated against cabinet constraints
- **Individual Height Control**: Set specific drawer heights or use intelligent auto-distribution
- **Advanced Groove System**: Precision groove cutting in front, left, and right pieces for perfect base panel assembly
- **Slide Clearance Management**: Configurable clearance on both sides for different slide hardware types
  
![Drawer](https://github.com/fabio1994/WoodWorkingWizard/blob/main/Images/5.jpg?raw=true)

#### **Front Panel Innovation**
- **Complete Face Coverage**: Front panels cover the entire cabinet opening area (excluding top/bottom panels)
- **Perfect Drawer Alignment**: Each front panel section automatically centers on its corresponding drawer
- **User-Controlled Spacing**: Configurable gaps between front panel sections for professional appearance
- **Uniform Sizing**: All front panel sections have equal height for consistent, high-end look


![4](https://github.com/fabio1994/WoodWorkingWizard/blob/main/Images/4.jpg?raw=true)

#### **Door System Improvements**
- **Corrected Positioning**: Fixed critical issue where doors appeared on floor instead of cabinet front
- **Realistic Visualization**: Doors display in 45° open position for better design review
- **Enhanced Double Doors**: Proper hinge points (left door hinges left, right door hinges right)
- **Material Consistency**: Doors automatically match cabinet material thickness

#### **Parameter Validation System**
- **Real-Time Validation**: Live constraint checking prevents impossible configurations
- **Smart Limits**: Drawer depths automatically limited to available cabinet space
- **Height Distribution**: Intelligent spacing calculations when using custom drawer heights
- **User Feedback**: Clear error messages and warnings for constraint violations

---

## How WoodWorkingWizard Works

Discover how our plugin revolutionizes custom furniture design in Fusion 360, guiding you step by step through the complete process.

### Step One: Start Your Project
Begin by creating the basic structure of your furniture piece, setting dimensions and shapes with intuitive tools integrated into the plugin.

### Step Two: Customize Details  
Add finishes, joints, and unique materials to model your piece, leveraging specialized woodworking functions for professional results.

### Step Three: Export and Produce
Complete your project by exporting files ready for production, optimized for artisanal manufacturing and workshop use.

---

## Product Features

### 🛠️ **Automated Cabinet Creation**

**Complete Cabinet System** ⭐ *Enhanced in v2.1.1*
- Full cabinet structures: base, sides, back, top with precision insets
- Interior options: shelves, advanced drawers, or structure-only
- Smart material thickness calculations throughout
- Auto-generated Fusion 360 parameters for all dimensions
- Real-time parameter validation with constraint checking

**Advanced Drawer System** ⭐ *NEW in v2.1.1*
- **5-Piece Construction**: Front, back, left, right, and base panels
- **Precision Groove Cutting**: Automated grooves in front and side pieces for base assembly  
- **Custom Depth Control**: User-selectable depths with automatic validation against cabinet limits
- **Height Flexibility**: Individual drawer height control or intelligent auto-distribution
- **Slide Clearance**: Configurable clearance on both sides for various slide hardware
- **Smart Base Assembly**: Base panel sized to fit into grooves perfectly

**Front Panel System** ⭐ *NEW in v2.1.1*
- **Full Face Coverage**: Panels cover entire cabinet face excluding top/bottom
- **Perfect Alignment**: Each panel section centers automatically on its drawer
- **User-Controlled Spacing**: Configurable gaps between front panel sections
- **Uniform Appearance**: Equal-height panels for professional, high-end look
- **Material Matching**: Front panels use same thickness as drawer components

**Smart Door Generation** ⭐ *Enhanced in v2.1.1*
- **Corrected Positioning**: Doors now appear at cabinet front (fixed floor placement bug)
- **Single & Double Options**: Choose between single full-width or double half-width doors
- **Realistic Display**: 45° open position for better visualization
- **Proper Hinge Points**: Left door hinges left, right door hinges right for double doors
- **Automatic Sizing**: Doors match cabinet material thickness automatically

**Toekick Frame Builder**
- Hollow frame structures with precise measurements
- Four-piece construction with perfect corner joints
- Customizable height, depth, and thickness settings

**Multi-Unit Support**
- Work seamlessly in millimeters, centimeters, or inches
- Automatic unit conversion and validation throughout workflow

### 📋 **Intelligent Cut List & Nesting**

**Revolutionary Pure-Python Engine (New in v2.1.0)**
- Zero external dependencies - everything runs natively in Fusion 360
- Uses rectpack library when available, with built-in CCOA fallback
- No Node.js, no Python installations required

**Advanced Nesting Algorithms**
- **Corner-Occupying Action (CCOA) Packer**: Candidate-corner placement with skyline fallback
- **Smart Consolidation**: Backfills earlier sheets to minimize waste
- **Rotation-Aware Processing**: 90° rotations considered automatically when allowed
- **Multi-Attempt Optimization**: 128 optimization attempts for superior layouts (hidden from UI)

**Production-Ready Output**
- Single CSV file with comprehensive cut list data
- "Panels (Grouped by Sheet)" section for efficient production planning
- Material preservation from original components
- Accurate quantity calculations with waste reporting

### ⚙️ **3D Visualization & Production Planning**

**Interactive 3D Preview**
- Transparent sheet materials for easy viewing
- Properly spaced components with kerf considerations
- Real-time visualization updates as you adjust parameters
- Material colors preserved from original components

**Configurable Settings**
- Default 244×122 cm (8'×4') sheets with full customization
- Adjustable kerf spacing (blade width) settings
- Customizable edge margins for safety
- Vertical sheet spacing control for 3D views

**Professional Sheet Layouts**
- Standard plywood and MDF sheet sizes supported
- Custom sheet dimensions for specialty materials
- Automatic waste calculation and reporting
- Optimal part placement with minimal scrap

---
## How It Works

### **Step 1: Design Creation**
1. Launch WoodWorking Wizard from Fusion 360's Create panel
2. Select project type (Cabinet or Toekick)
3. Enter dimensions and material specifications
4. Choose interior options (shelves, drawers, doors)
5. Wizard automatically creates parametric 3D model

![1](https://github.com/fabio1994/WoodWorkingWizard/blob/main/Images/1.jpg?raw=true)

### **Step 2: Cut List Generation**
1. Select bodies from your design
2. Choose measurement units (mm/cm/in)
3. Enable nesting layout optimization
4. Configure sheet sizes and cutting parameters
5. Generate comprehensive CSV cut list with quantities

![6](https://github.com/fabio1994/WoodWorkingWizard/blob/main/Images/6.jpg?raw=true)


### **Step 3: 3D Visualization**
1. View optimized sheet layouts in 3D
2. Inspect part placement and spacing
3. Verify material assignments and quantities
4. Export for production planning

### **Step 4: Production**
1. Use cut list for material ordering
2. Follow 3D layout for efficient cutting
3. Reference part dimensions for assembly
4. Track material usage and waste
---
## Technical Specifications

### **System Requirements**
- **Software**: Autodesk Fusion 360 (Windows or macOS)
- **Operating System**: Windows 7/8/10/11 or macOS 10.14+
- **Hardware**: Standard Fusion 360 requirements
- **Dependencies**: None - fully self-contained
