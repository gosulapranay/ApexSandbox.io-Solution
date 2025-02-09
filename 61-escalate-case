public void escalateIfMeetsCriteria(Case c) {
    if(c.Type == 'Mechanical' || c.Type == 'Electrical'){
        if(c.Reason == 'Breakdown'){
            if(c.Status == 'In Progress'){
                c.IsEscalated = true;
            }
        }
    }
}