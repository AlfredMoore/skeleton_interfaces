# skeleton_interfaces

## skeleton message

MultiHumanSkeleton
-----
 * std_msgs/Header header
 * HumanSkeleton[] multi_human_skeleton
 
 
 HumanSkeleton
-----
 * uint32 human_id
 * geometry_msgs/Point32 human_center
 * geometry_msgs/Point32[] keypoint_data
 * bool[] keypoint_mask
