# kratos_localisation

Configure the params file for making localization better.
Have uploaded the tbot.map for use.
The launch files for move_base and amcl are configured.
Provide goal the goal as a 2D nav goal.

To turn on localization for amcl, un-comment the start_ekf_localization file.

The jumping that occurs during running simulation in rviz is due to tf_frame difference between map frame and odom frame. To fix this, we would require a more accurate gmapping.
