# Step 1: Requirements clarifications
## Functional Requirements
	- Tweet: create
	- Tweet: delete
	- Timeline: read Home
	- Timeline: read User
	- mark favorite tweet
	- 
## Non-functional Requirements
## Extended Requirements

# Step 2: Back-of-the-envelope estimation
- DAU: 200M
- tweets per day DAU * 5
- Storage: 
	- tweet view: DAU * (2 self + 5 others') (visited timeline) * 20 (tweets/timeline) = 28B (tweets/day)
	- size for tweet: DAU (280 + 30) = 30 GB/day
- Bandwidth:


# Step 3: System interface definition

# Step 4: Defining data model

# Step 5: High-level design

# Step 6: Detailed design

# Step 7: Identifying and resolving bottlenecks