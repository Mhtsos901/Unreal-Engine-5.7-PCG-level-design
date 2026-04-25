# Unreal Engine 5 – PCG Procedural Level Design

A learning project focused on procedural environment generation in Unreal Engine 5.  
Built to explore the PCG framework, landscape tooling, and performance optimization techniques.

**[Watch the full demo on YouTube](https://youtu.be/glvP2pPKCW4)**

---

## Screenshots

![Overview](Screenshot%20%28301%29.png)
![Landscape](Screenshot%20%28302%29.png)
![PCG detail](Screenshot%20%28303%29.png)
![Materials](Screenshot%20%28304%29.png)

---

## What I worked on

**Procedural Content Generation (PCG)**
- Built PCG graphs with hierarchical rule layers to place foliage, rocks, and props across the landscape procedurally
- Used point cloud filtering and density controls to achieve natural, non-repetitive distributions

**Auto-Material & Runtime Virtual Textures (RVT)**
- Created a landscape auto-material that blends rock, grass, and mud layers based on slope and height data
- Used Runtime Virtual Textures to project materials seamlessly across meshes and terrain without visible seams or performance cost

**Level of Detail (LOD) & Performance**
- Configured per-mesh LODs and Hierarchical LOD (HLOD) to maintain stable frame rates across large procedurally generated scenes
- Managed draw call budgets for dense foliage areas

**Landscape Sculpting & Painting**
- Sculpted and painted the terrain using UE5 editor tools
- Wired Blueprint logic for runtime dynamic behaviour on selected assets

---

## Tech

`Unreal Engine 5` · `PCG Framework` · `Blueprints` · `Runtime Virtual Textures` · `HLOD / LODs` · `Landscape Tools`

---

## Notes

This was a learning project — the goal was to get hands-on with UE5's procedural toolset, not to ship a game.  
The source project files are not included due to size, but the full demo is on YouTube.
