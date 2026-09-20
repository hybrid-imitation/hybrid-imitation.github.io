# hybrid-imitation.github.io

Project website for **Hybrid Imitation Learning: Teleoperation Augmentation Primitives that Policies Learn to Trigger**
(Jonne Van Haastregt, Bastian Orthmann, Michael C. Welle, Yuchong Zhang, Danica Kragic; INCAR Robotics AB and KTH Royal Institute of Technology).

- `index.html`: landing page (overview, TAP types, simulation study, real-robot validation, industrial deployment).
- `vial_aspiration.html`, `open_container_liquid_transfer.html`, `unscrew_cap.html`: all real-robot rollouts, TAP-triggering policy vs baseline.
- `simulation_rollouts.html`: one reel per condition of the paper's three simulation tables (both tasks), plus the two
  unassisted-vs-TAP side-by-side reels. Generated, together with the `SIM-REELS` block of `index.html`, by
  `ICRA2026/video/build/site_html.py` in the research tree (condition table, commands and audit: `ICRA2026/video/STORYBOARD.md`,
  section "Website material"). Do not edit the generated parts by hand.
- `files/`: figures; `videos/`: real-robot rollout videos, `videos/sim/`: simulation reels and posters, `videos/sim/all/`: one mosaic per condition with all 500 evaluation trials of training seed 1,
  `videos/hybrid_imitation_icra2027.mp4`: the accompanying video (non-anonymous cut); `assets/`: HTML5 UP "Hyperspace" template.

Every number on the site is taken from the paper's generated tables (`generated/*.tex`) and result tables.
