---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

- **Improved Conflict-Based Search for the Virtual Network Embedding Problem.**

  **Yi Zheng**, Srivatsan Ravi, Erik Kline, Lincoln Thurlow, Sven Koenig and T. K. Satish Kumar
  
  In proceedings of the Thirty-Second International Conference on Computer Communications and Networks (ICCCN-2023).

- **Priority-Based Search for the Virtual Network Embedding Problem.**

  **Yi Zheng**, Hang Ma, Sven Koenig, Erik Kline and T. K. Satish Kumar
  
  In proceedings of the Thirty-Third International Conference on Automated Planning and Scheduling (ICAPS-2023).

- **Conflict-Based Search for the Virtual Network Embedding Problem.**

  **Yi Zheng**, Srivatsan Ravi, Erik Kline, Sven Koenig and T. K. Satish Kumar.  
  
  In Proceedings of the International Conference on Automated Planning and Scheduling (ICAPS), 2022.

- **(Dis)Appearables: A Concept and Method for Actuated Tangible UIs to Appear and Disappear based on Stages**.

  Ken Nakagaki, Jordan L Tappa, **Yi Zheng**, Jack Forman, Joanne Leong, Sven Koenig, and Hiroshi Ishii.
  
  In CHI Conference on Human Factors in Computing Systems (pp. 1-13), 2022.

- **Artificial Intelligence and Automation**.

  S. Koenig, S.-H. Chan, J. Li and **Yi Zheng**.
  
  In Handbook of Automation, S. Nof (editor), Springer, 2021.

- **Scalable Rail Planning and Replanning: Winning the 2020 Flatland Challenge (Winner of the NeurIPS’20 Flatland Challenge)**.

  Jiaoyang Li, Zhe Chen, **Yi Zheng**, Shao-Hung Chan, Daniel Harabor, Peter J. Stuckey, Hang Ma and Sven Koenig.

  International Conference on Automated Planning and Scheduling (ICAPS), pages 477-485, 2021.

  A short version appeared at Symposium on Combinatorial Search (SoCS), pages 179-181, 2021.

  [[code]](https://github.com/Jiaoyang-Li/Flatland)


- **Flatland Competition 2020: MAPF and MARL for Efficient Train Coordination on a Grid World.**

  Florian Laurent, Manuel Schneider, Christian Scheller, Jeremy Watson, Jiaoyang Li, Zhe Chen, **Yi Zheng**, Shao-Hung Chan, Konstantin Makhnev, Oleg Svidchenko, Vladimir Egorov, Dmitry Ivanov, Aleksei Shpilman, Evgenija Spirovska, Oliver Tanevski, Aleksandar Nikov, Ramon Grunder, David Galevski, Jakov Mitrovski, Guillaume Sartoretti, Zhiyao Luo, Mehul Damani, Nilabha Bhattacharya, Shivam Agarwal, Adrian Egli, Erik Nygren and Sharada Mohanty.

  NeurIPS 2020 Competition and Demonstration Track, PMLR, volume 133, pages 275-301, 2021.

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
