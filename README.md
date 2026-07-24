# IETF126-sidemeeting
Repository for Networking for AI side meeting during IETF 126

The idea to have this side meeting is to continue the discussion about research directions on networking for AI that should happen in the IRTF, as a complement of the activities ongoing in the IETF. 

## Logistics: 
* __Room:__  Park Suite 4
* __Remote participation:__  https://ietf.webex.com/meet/sidemeetings1 (IETF Webex)
* __Notes:__ TBD

  ## Mailing list
  Discussions around the side meeting should happen on the [Net4AI mailing list](https://mailman3.irtf.org/mailman3/lists/net4ai.irtf.org/).

## Agenda:

| Time | Topic | Slides |
| --- | --- | --- |
| 12:00 – 12:05 _(5 min)_ | Meeting setup and introduction of the meeting  | N/A |
| 12:05 – 12:35 _(30 min)_ | _Gym & Benchmarks  for Network Agents_ by Dario Rossi _(Huawei)_ | [Slides](https://github.com/IRTF-net4AI/IETF126-sidemeeting/blob/main/slides/IETF126-NetworkingAgents.pdf) |
| 12:35 – 13:45 _(70 min)_ | _Discussion on charter for future Research Group_ | [Slides](https://github.com/IRTF-net4AI/IETF126-sidemeeting/blob/main/slides/Net4AI-side-meeting.pdf) |

## Talk abstract

### Gym & Benchmarks  for Network Agents

This talk emphasizes that, to increase generalization capabilities of an agent in an automated fashion, it is necessary to minimize human intervention in the agentic evolution loop: Rather, human effort is needed to define benchmarks and evaluations practices. 
IETF is the right forum for vendors, ISPs, OTT, academia & (power) users to discuss and agree on useful realistic benchmarks.

Additionally, instead of showing the shiny aspects of agents, we prefer to show the dark side of their evaluation, _i.e._, when things can go wrong and benchmaxxing creates illusion of progress, or silent error and oddities plague the agent execution. 
For all these cases, we argue that, before classic accuracy metrics, community and benchmarks should explicitly track, count and expose failure modes to increase trust and ultimately foster adoption. 
The talk concludes with a bitter lesson (computational progress outpace human design), having nevertheless a sweet taste (open weight models progress is exponential, so that on-prem agents are a near future possibility).
