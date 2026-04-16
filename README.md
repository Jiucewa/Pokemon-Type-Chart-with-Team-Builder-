# Pokemon-Type-Chart-with-Team-Builder-
This project is a fully interactive web application designed to help Pokemon players master type matchups and build strategically sound teams. Built as a single HTML file with no external dependencies, it combines two essential tools into one polished, modern interface.

The first component is a complete Type Chart displaying all 18 Pokemon types in an 18×18 grid format. Each cell represents the effectiveness of an attacking type against a defending type, with intuitive color-coding: green for super effective hits (2x damage), orange for resisted hits (0.5x), gray for immunities (0x), and additional indicators for extreme cases like 4x weaknesses or 0.25x resistances. Users can hover over any cell to highlight the corresponding row and column, making it easy to trace offensive and defensive matchups. A tooltip appears with plain-language explanations, and the entire grid is keyboard-accessible for inclusive navigation.

The second and more powerful component is the Team Builder. Users can configure up to six Pokemon slots, each with primary and optional secondary type selections. As types are assigned, the application automatically calculates the team's combined defensive profile. It aggregates weaknesses, resistances, and immunities across all team members, presenting them in organized sections. Critically, the tool identifies coverage gaps—if multiple Pokemon share a common weakness, a warning alert appears, such as "Your team has 3 Pokemon weak to Ground!" This helps players spot vulnerabilities they might otherwise miss.

<img width="1170" height="932" alt="image" src="https://github.com/user-attachments/assets/69f5158f-015a-4d7c-8098-e63f790f7974" />
<img width="1170" height="804" alt="image" src="https://github.com/user-attachments/assets/7fb4baba-85bd-421e-8720-b6fb38e19d90" />

