## Multi-Client Conflict Management Implementation

### Overview
This PR implements conflict management features for multi-client synchronization scenarios in the Turso PHP client.

### Type of Change
- [ ] New conflict detection mechanism
- [ ] Conflict resolution strategy
- [ ] Client state synchronization
- [ ] Recovery and retry logic
- [ ] Integration with existing sync mechanism
- [ ] Other (please describe)

### Description
<!-- Provide a detailed description of the changes -->

### Motivation & Context
<!-- Why are these changes needed? What problem do they solve? -->

### Conflict Management Strategy
<!-- Describe the approach for handling conflicts between multiple clients -->

- **Detection Method**: <!-- How are conflicts detected? -->
- **Resolution Policy**: <!-- What strategy is used to resolve conflicts? -->
- **Client Priority**: <!-- How are conflicting clients prioritized? -->
- **State Recovery**: <!-- How is consistent state recovered after conflict resolution? -->

### Testing

#### Unit Tests
- [ ] Conflict detection tests added
- [ ] Resolution logic tests added
- [ ] State consistency tests added
- [ ] Edge case tests included

#### Integration Tests
- [ ] Multi-client synchronization scenarios tested
- [ ] Conflict scenarios tested (concurrent writes, network issues, etc.)
- [ ] State consistency verified across multiple clients
- [ ] Rollback and recovery tested

#### Manual Testing
- [ ] Tested with multiple concurrent clients
- [ ] Verified state consistency
- [ ] Tested failure scenarios
- [ ] Performance validated

### Code Changes
<!-- Provide a summary of key code changes -->

#### Files Modified
- [ ] List of files changed

#### New Files
- [ ] List of new files added

### Performance Impact
<!-- Any performance considerations? -->

- **Memory**: <!-- Impact on memory usage -->
- **CPU**: <!-- Impact on CPU usage -->
- **Network**: <!-- Impact on network traffic -->
- **Latency**: <!-- Impact on response time -->

### Breaking Changes
- [ ] This PR contains breaking changes
  - If checked, please describe the breaking changes and migration path:

### Backwards Compatibility
- [ ] Changes are backwards compatible
- [ ] Changes maintain existing API contracts
- [ ] Deprecations handled properly (if applicable)

### Documentation
- [ ] Inline code comments added
- [ ] README updated (if applicable)
- [ ] API documentation updated
- [ ] Migration guide created (if breaking changes)
- [ ] Examples added/updated

### Related Issues
<!-- Link related issues here using #issue-number -->

Closes #
Related to #

### Checklist
- [ ] My code follows the project's code style
- [ ] I have self-reviewed my own code
- [ ] I have commented my code, particularly in hard-to-understand areas
- [ ] I have made corresponding changes to the documentation
- [ ] My changes generate no new warnings or errors
- [ ] I have added tests that prove my fix is effective or that my feature works
- [ ] New and existing unit tests passed locally with my changes
- [ ] Any dependent changes have been merged and published
- [ ] The PR title clearly describes the changes

### Reviewers Notes
<!-- Any additional notes for reviewers? -->

### Screenshots/Logs (if applicable)
<!-- Add screenshots or logs demonstrating the changes -->

---

**Reviewer Checklist:**
- [ ] Code changes are clear and follow project conventions
- [ ] Tests are comprehensive and passing
- [ ] Documentation is complete and accurate
- [ ] Conflict management strategy is sound
- [ ] No regression risks identified
- [ ] Ready to merge
