* For lane fit fxn, need to add feed-forward of curve fits from previous image frame
  * I think we could get away with just adding some form of averaging here as well - whatever is easier
* Limit the window that we read the lane lines further (in y-axis). Uncertainty in points as y value diminishes is causing problems with line fits.
* ~~For lane fit fxn, need to add guess at x value for y=ymax - currently end up with 2 fits starting from the beginning of a single lane~~