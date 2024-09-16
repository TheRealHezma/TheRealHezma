const hemza = {
  name: "Hemza Mansour",
  pronouns: "he" | "him",
  code: ["Javascript", "HTML", "CSS", "Python"],
  tools: ["React", "Redux", "Node", "Docker"],
  architecture: ["microservices", "event-driven", "design system pattern"],
  methodologies: ["Agile", "Scrum", "Kanban"],
  techCommunities: ["Reactiflux", "XDA"],
  challenge: "To create an app for the iWatch that will have over a million downloads"
};

console.log(
  `Hi, I'm ${hemza.name} (pronouns: ${hemza.pronouns}). I am proficient in ${hemza.code.join(", ")} ` +
  `and I use tools like ${hemza.tools.join(", ")}. I follow architectural patterns such as ${hemza.architecture.join(", ")} ` +
  `and apply development methodologies like ${hemza.methodologies.join(", ")}. ` +
  `I'm active in tech communities such as ${hemza.techCommunities.join(" and ")}, and currently, ` +
  `I'm working on a challenge: ${hemza.challenge}.`
);
