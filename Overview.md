

This is an overview of the project, it's goals and progress. This Wiki will be used to document the history of the project's development as well as outlining future objectives.

# 1 Introduction #
**Bastion** places two players (or one player vs. AI) head-to-head in an all out battle for territory and conquest. One player defends his heavily fortified position against the enemy's constant siege attacks. This dichotomy of attack and defense is a pattern as old as warfare itself. And just as the great military forces of history have applied new technologies, tactics and cunning to their efforts, so will the player be tasked with the customization and renovation of his encampment. The player must adapt, manage resources wisely and perfect his tactics if he hopes to stand any chance of survival.

---

# 2 Project Breakdown #
| **Property** | **Description** |
|:-------------|:----------------|
| Engine | UnrealEngine 3 |
| Development Tools | Unreal Development Kit |
| Genre | FPS, RTS |
| Scripting Language | UnrealScript |
| Start Date | Feb 2011 |

> ## 2.1 Details ##
> Here we will elaborate on the pros and cons of each project property and perhaps engage in debate about each decision.
> > ### 2.1.1 Engine ###
> > For the purposes of this project we have selected the UnrealEngine 3 code base. The reasons for this decision are it's price (can't beat free), it's portability (allows easy porting to X360) and its precedence as a mainstay in the FPS game development community. It was, after all, used to create the infamous Unreal Tournament series of games, specifically UT3. The difficulty with using this engine will most likely originate from the implementation of RTS elements, requiring a disembodied, third person omniscient view.
> > ### 2.1.2 Development Tools ###
> > This stands to reason as we have decided upon the Unreal3 engine and the Unreal Development Kit is the tool set made specifically for its use. However, it must be mentioned for our 3D artists that our modelling work is to be done entirely in 3DS Max if at all possible and, if not, to be exported as a .3DS if support for this format or conversion to this format is available with your software suite. If not, .OBJ should suffice. Material and sketch work is to be done in Photoshop (any version CS3+) and committed to the resource database according to the following schema:
| **Asset**            | **Required Files**         |
|:---------------------|:---------------------------|
| Texture/Material   | .TIFF + .PSD             |
| Material Maps      | .TIFF (match resolution) |
| Models             | .3DS or .OBJ             |
| Concept Images     | .PNG + .PSD              |
| Interface Elements | .SWF                     |

---

# 3 Feature Set #
<sup>For a full list of game features and descriptions, see GameFeatures.</sup>