# Flexible Load Units

In exceptional transports goods are usually considered while loaded on individual wagons. Goods longer than the maximum loading length of the wagon, and beyond the wagon length spread on several wagons can also be transported by rail, when some restrictions are observed. Restrictions for long goods exceeding wagon loading length vary depending on the flexibility of the load.

## Definition

Flexible load units which are loaded on more than two wagons are transported as exceptional consignments.

## Use Cases

Flexible units like:

- rails longer than 36 m
- steel rods for concrete
- plastic pipes and etc

when loaded on sets of several wagons with collapsible end boards or stanchions they are to be transported as exceptional consignments. On networks of: BDZ, EWS, FS, HZ, MZ, ZFBH, ZRS, ZS, ÖBB, PKP, ADIF, ASTOC, SNCB, SNCF, SZ and TCDD, load units loaded on more than two wagons are considered exceptional consignments, even when they are forwarded in block trains.

On certain railways Other National Rules apply for such transports in line with UIC Loading Guidelines provisions.

## Long Rails

Steel is more flexible than one may think at a first glance. The longer the rails are the longer wagon sets are needed to transport them. For example for rails long 120 m it may take from 6 to 9 wagons to compose a wagon set. Rails are transported in layers on the flat wagon sets. Rail layers are supported by fixing blocks and supportive frames. Fixing long rails in supportive frames, neither too loosely nor to firmly, allows rails to simultaneously shift on curves to accommodate to small curves such as with radius of 150 m.
See how rails in layers behave on S curve at the siding of Voelstapine AG.

In the case of the flexible goods which cover the coupling zone longitudinal play must be taken into account. The transport units must be coupled in such a way that the buffers are in slight contact. This is important in order to maintain an even load on the wheel sets of the individual wagons throughout the set. If there are significant variations in the height of buffers, it could lead to the infrastructure manager’s (IM) rolling stock detection and monitoring systems registering false axle overload conditions. This might be detected in certain wagons that are carrying long, flexible loads within the set. It is virtually impossible to correct rail's loading method while on wagon set during transport, and therefore such situations should be actively avoided.

## Consignment Application

|  Code  | Declare in application                                                                                                                       |
| :----: | :------------------------------------------------------------------------------------------------------------------------------------------- |
|  #1a   | Type and total length of the shipment in meters                                                                                              |
|   #5   | All axles for the wagon set                                                                                                                  |
|  #6a   | Summed up length of the wagon set                                                                                                            |
|   #7   | Tare weight of single wagon                                                                                                                  |
|   #8   | The total mass of the load on the wagon set / progressive, variants possible                                                                 |
|  #11   | The total length of the load on the wagon set                                                                                                |
| #12-15 | Loading gauge not exceeded                                                                                                                   |
|  #24   | Reduced speed for the wagon set                                                                                                              |
|  #29   | •These consignments may not be subject to hump or fly shunting, nor may they collide with other vehicles that have been fly or hump shunted. |
|        | •Trains including these transport units may not be pushed.                                                                                   |
|        | •Wagon sets must not be separated                                                                                                            |
