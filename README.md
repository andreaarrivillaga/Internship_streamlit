# Youtube Creator Topology 

This project provides an interactive Streamlit dashboard for visualizing and analyzing a directed collaboration network of YouTube content creators.

Nodes: Individual YouTube channels (identified by channel_id).
Edges: Directed relationships between channels.
  • collab_link – Explicit references (links or @mentions) in video descriptions.
edge_weight = Number of times the source channel referenced the target channel across scanned descriptions.

Thus, edge_weight represents frequency strength of the relationship.

Interpretation of the Resulting Graph
The resulting graph is:
  • Directed (A → B means A referenced B)
  • Weighted (frequency of references)
  • Multi-source (relationships originate from all channels in the cohort, not only the seed)

This is a reference-based interaction topology.






