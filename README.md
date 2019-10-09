# DrawTreeOfBranches
This class takes arrays of node with ID in any order, and draw related tree and writes the nodes information instead of leafs. Note that, right know the maximum level for the tree is 3 you can change it to any level that you want.


1- Note that, the node must has an ID, i.e. each node has a nodeID, and may has two childeren,
fatherNodeID = a;
childernNodeID1= 2 * a + 1;
childernNodeID2= 2 * a + 2;

2- right now the maximum level that it can draw is 3, you can change it, be aware the biger the level the wider the tree


3- I send an arraylist of my other class (Branch) with ID and differnt info, you can redefine the class Branch for yourself,

the demonstration for the tree is as fallows:

                                                            id Brtype
                                                               val
                                                             i-h/Val
                                                         dd-d/d-t/w-h-t
                                                             if MIP
                                                               /\
                                                              /  \
                                                             /    \
                                                            /      \
                                                           /        \
                                                          /          \
                                                         /            \
                                                        /              \
                                                       /                \
                                                      /                  \
                                                     /                    \
                                                    /                      \
                                                   /                        \
                                                  /                          \
                                                 /                            \
                                                /                              \
                                               /                                \
                                              /                                  \
                                             /                                    \
                                            /                                      \
                                           /                                        \
                                          /                                          \
                                         /                                            \
                                        /                                              \
                                       /                                                \
                                      /                                                  \
                                     /                                                    \
                                    /                                                      \
                                   /                                                        \
                                  /                                                          \
                                 /                                                            \
                                /                                                              \
                              1 Mi                                                            2 Mi
                             1278,5                                                          1278,5
                               <0                                                              >1
                              3-2-4                                                           3-2-4
                                                                                                
                               /\                                                              /\
                              /  \                                                            /  \
                             /    \                                                          /    \
                            /      \                                                        /      \
                           /        \                                                      /        \
                          /          \                                                    /          \
                         /            \                                                  /            \
                        /              \                                                /              \
                       /                \                                              /                \
                      /                  \                                            /                  \
                     /                    \                                          /                    \
                    /                      \                                        /                      \
                   /                        \                                      /                        \
                  /                          \                                    /                          \
                 /                            \                                  /                            \
                /                              \                                /                              \


                                                                              5 Mi                            6 Mi
                                                                             1278,5                          1278,5
                                                                               <0                              >1
                                                                             3-2-14                          3-2-14
                                                                                                                
                                                                               /\                              /\
                                                                              /  \                            /  \
                                                                             /    \                          /    \
                                                                            /      \                        /      \
                                                                           /        \                      /        \
                                                                          /          \                    /          \
                                                                         /            \                  /            \
                                                                        /              \                /              \




